#!/usr/bin/python

"""
Greatest productivity script ever created. Adds whole bunch of entries to /etc/hosts
to block distracting sites. 

To block sites, run:
sudo python3 concentration.py block

To unblock sites, run:
sudo python3 concentration.py unblock

Install the SuperFocus Chrome extension to track time, block sites and hide distractions
https://getsuperfocus.com/install/
"""

import sys

lines = open('/etc/hosts').readlines()
lines = [line.strip() for line in lines]

# Finance sites
domains_0 = [
  'x.com', 'finance.yahoo.com', 'seekingalpha.com', 'economictimes.indiatimes.com', 'moneycontrol.com', 'cnbc.com', 'bloomberg.com',
  'reddit.com', 'robinhood.com', 'asia.nikkei.com', 'fool.com', 'zerohedge.com', 'livemint.com', 'finchat.io',
]

# News sites
domains_1 = [
  'nytimes.com', 'snapchat.com', 'hindustantimes.com', 'scmp.com', 'similarweb.com',
  'latimes.com', 'nypost.com', 'abs.twimg.com', 'liveuamap.com', 't.me', 'linkedin.com', 'instagram.com', 'wsj.com',
  'retaildive.com', 'fiercevideo.com', 'fiercetelecom.com', 'news.ycombinator.com', 'thelayoff.com', 'windy.com'
]

# Entertainment sites
domains_2 = ['quora.com', 'youtube.com', 'twitch.tv',]

header = """##
# Host Database
#
# localhost is used to configure the loopback interface
# when the system is booting.  Do not change this entry.
##
127.0.0.1	localhost
255.255.255.255	broadcasthost
::1             localhost

"""

if len(sys.argv) != 2:
  print("Usage: sudo python3 concentration.py [block/unblock]")
  sys.exit(1)


if sys.argv[1] == "block":
  print("Block sites")
  domains = domains_0 + domains_1 + domains_2
elif sys.argv[1] == "unblock":
  print("Unblocking sites")
  domains = []

block_list = []
block_list += ['0.0.0.0 ' + domain for domain in domains]
block_list += [':: ' + domain for domain in domains]
block_list += ['0.0.0.0 www.' + domain for domain in domains if not domain.startswith('www.')]
block_list += [':: www.' + domain for domain in domains if not domain.startswith('www.')]

open('/etc/hosts', 'w').write(header + '\n'.join(block_list))
print("Done")
