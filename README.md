
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
            <title>Unblocked Games FreezeNova</title>
        <meta name="description" content="Play unblocked games on FreezeNova. Join our community of free online games and become a passionate gamer!" />
        
        <meta name="generator" content="Publii Open-Source CMS for Static Site" />
<link rel="stylesheet" href="./media/plugins/staticSearch/static.search.min.css" />
        
        
        
	        <link rel="shortcut icon" href="./media/website/favicon-1.ico" type="image/x-icon" />
                <link rel="next" href="./page/2/index.html">
        <link rel="stylesheet" href="./assets/css/style.css?v=1efb486b1d1dfcca462baef5c982405a">       
        <script type="application/ld+json">{"@context":"http://schema.org","@type":"Organization","name":"Unblocked Games FreezeNova","logo":"./media/website/unblocked-games-freezenova-logo.webp","url":"./index.html"}</script>        
        
			  <script>
				window.wgAutoMidroll = false;
			  </script>
        <meta http-equiv="Content-Security-Policy" content="upgrade-insecure-requests">

<script type="text/javascript" async>
    if (window.location.pathname.includes("game-developers.html") == false) {
        if (window.location.pathname.includes("index.html.abc") == false)
        {
            !function(e,t){a=e.createElement("script"),m=e.getElementsByTagName("script")[0],a.async=1,a.src=t,m.parentNode.insertBefore(a,m)}(document,"https://universal.wgplayer.com/tag/?lh="+window.location.hostname+"&wp="+window.location.pathname+"&ws="+window.location.search);
        }
    }
</script>

<!-- Google tag (gtag.js) -->
<script>
        (function() {
            // Check the domain name
            var scriptSrc, configId;

            if (window.location.hostname === 'unblocked-games.s3-accelerate.amazonaws.com') {
                // Google Analytics ID for unblocked-games.s3-accelerate.amazonaws.com
                scriptSrc = 'https://www.googletagmanager.com/gtag/js?id=G-S5X25J1HQ5';
                configId = 'G-S5X25J1HQ5';
            }
    		else {
    			if (window.location.hostname === 'freezenova.github.io') {
                    // Google Analytics ID for freezenova.github.io
                    scriptSrc = 'https://www.googletagmanager.com/gtag/js?id=G-YXFREC5MSS';
                    configId = 'G-YXFREC5MSS';
                }
    			else
    			{
    				if (window.location.hostname === 'd9k5uuutyxogn.cloudfront.net') {
                        // Google Analytics ID for d9k5uuutyxogn.cloudfront.net
                        scriptSrc = 'https://www.googletagmanager.com/gtag/js?id=G-KLY0GTQKFT';
                        configId = 'G-KLY0GTQKFT';
                    }
                    else
                    {
                        // Google Analytics ID for other domains
                        scriptSrc = 'https://www.googletagmanager.com/gtag/js?id=G-Z1FT2YYNFS';
                        configId = 'G-Z1FT2YYNFS';
                    }
				}
            }

            // Create the script element for Google Analytics
            var gaScript = document.createElement('script');
            gaScript.async = true;
            gaScript.src = scriptSrc;
            document.head.appendChild(gaScript);

            // Create the script element for gtag configuration
            gaScript.onload = function() {
                window.dataLayer = window.dataLayer || [];
                function gtag(){dataLayer.push(arguments);}
                gtag('js', new Date());
                gtag('config', configId);
            };
        })();
</script>

<script>
    function redirectToIndex() {
        var currentUrl = window.location.href;
        var path = window.location.pathname;
        var hostname = window.location.hostname;
        
        if (hostname === 'freezenova.github.io') {
            if (path.endsWith('/') && !path.endsWith('/index.html')) {
                window.location.replace(currentUrl + 'index.html');
            }
        }
    }

    redirectToIndex();
</script>


<script>
        (function() {
            if (window.location.hostname !== 'freezenova.s3.amazonaws.com' &&
    			window.location.hostname !== 'unblocked-games.s3.amazonaws.com') {
                var canonicalLink = document.createElement('link');
                canonicalLink.rel = 'canonical';
                
                if (window.location.pathname === '/' || window.location.pathname === '/index.html') {
    				if (window.location.hostname !== 'freezenova.github.io')
    				{
    					canonicalLink.href = 'https://unblocked-games.s3.amazonaws.com/index.html';
    					document.head.appendChild(canonicalLink);
    				}
                } else {
                    canonicalLink.href = 'https://unblocked-games.s3.amazonaws.com' + window.location.pathname;
    				document.head.appendChild(canonicalLink);
                }
            }
        })();
</script>


<script>
  // List of allowed domains
  var allowedDomains = [
    'unblocked-games.s3.amazonaws.com',
    'unblocked-games.s3-accelerate.amazonaws.com',
    'freezenova.github.io'
  ];

  // Function to add meta tags for specific domains and paths
  function addMetaTags() {
    var hostname = window.location.hostname;
    var pathname = window.location.pathname;

    // Check if the current hostname is not in the allowed list
    // and the pathname is not exactly the root or root index.html
    if (!allowedDomains.includes(hostname)) {
      // Create meta tag for noindex
      var metaNoIndexNoFollow = document.createElement('meta');
      metaNoIndexNoFollow.setAttribute('name', 'robots');
      metaNoIndexNoFollow.setAttribute('content', 'noindex, nofollow');

      // Append the meta tag to the head
      document.head.appendChild(metaNoIndexNoFollow);
    }
  }

  // Function to update the page title to include the domain name
  function updatePageTitle() {
    var hostname = window.location.hostname;

    // Check if the current hostname is not in the allowed list
    if (!allowedDomains.includes(hostname)) {
    	if (hostname == 'd9k5uuutyxogn.cloudfront.net')
        {
			var currentTitle = document.title;
      		document.title = `${currentTitle} - Cloud`;
        }
    	else
    	{
    		//var currentTitle = document.title;
      		//document.title = `${currentTitle} - ${hostname}`;
    	}
    }
    else if (hostname == 'unblocked-games.s3-accelerate.amazonaws.com')
    {
    	var currentTitle = document.title;
      	document.title = `${currentTitle} Accelerate`;
	}
    
  }
    
    function updatePageH1() {
		document.addEventListener('DOMContentLoaded', (event) => {
			const firstHeading = document.querySelector('h1');
            if (firstHeading) {
				var hostname = window.location.hostname;
				if (!allowedDomains.includes(hostname)) {
    				if (hostname == 'd9k5uuutyxogn.cloudfront.net')
    				{
    					firstHeading.innerHTML += ' <sup>Cloud</sup>';
    				}
    				else
    				{
    					//firstHeading.innerHTML += ` <sup>${hostname}</sup>`;
    				}
				}
				else if (hostname == 'unblocked-games.s3-accelerate.amazonaws.com')
				{
					firstHeading.innerHTML += ' <sup>Accelerate</sup>';
				}
            }
        });
  	}

  // Call the functions
  updatePageTitle();
  addMetaTags();
  updatePageH1();
</script>
    </head>
    <body style="background-color: black; background-image: url('./assets/img/bg_og.webp');">
        <header class="header" id="js-header">
   <style>
      .header.is-visible {
         background-image: url('./assets/img/bg_og.webp');
      }

      .header.is-hidden {
         background-image: url('./assets/img/bg_og.webp');
      }

      .navbar_mobile_sidebar {
         background-image: url('./assets/img/bg_og.webp') !important;
      }
   </style>
   <button aria-label="Open/Close sidebar" class="toggle_button" type="button"><svg viewBox="0 0 24 24"
         focusable="false" aria-hidden="true" class="button_svg">
         <path xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" clip-rule="evenodd"
            d="M19 4C19.5523 4 20 3.55229 20 3C20 2.44772 19.5523 2 19 2L3 2C2.44772 2 2 2.44772 2 3C2 3.55228 2.44772 4 3 4L19 4ZM20.47 7.95628L15.3568 11.152C14.7301 11.5437 14.7301 12.4564 15.3568 12.848L20.47 16.0438C21.136 16.4601 22 15.9812 22 15.1958V8.80427C22 8.01884 21.136 7.54 20.47 7.95628ZM11 13C11.5523 13 12 12.5523 12 12C12 11.4477 11.5523 11 11 11L3 11C2.44771 11 2 11.4477 2 12C2 12.5523 2.44771 13 3 13L11 13ZM20 21C20 21.5523 19.5523 22 19 22L3 22C2.44771 22 2 21.5523 2 21C2 20.4477 2.44771 20 3 20L19 20C19.5523 20 20 20.4477 20 21Z">
         </path>
      </svg>
      <svg viewBox="0 0 24 24" focusable="false" aria-hidden="true" class="mobile_toggle">
         <path xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" clip-rule="evenodd"
            d="M2 5C2 4.44772 2.44772 4 3 4H15C15.5523 4 16 4.44772 16 5C16 5.55228 15.5523 6 15 6H3C2.44772 6 2 5.55228 2 5ZM2 12C2 11.4477 2.44772 11 3 11L21 11C21.5523 11 22 11.4477 22 12C22 12.5523 21.5523 13 21 13L3 13C2.44772 13 2 12.5523 2 12ZM2 19C2 18.4477 2.44772 18 3 18L21 18C21.5523 18 22 18.4477 22 19C22 19.5523 21.5523 20 21 20L3 20C2.44772 20 2 19.5523 2 19Z">
         </path>
      </svg></button>
   <a href="./index.html" class="logo">
      <img src="./media/website/unblocked-games-freezenova-logo.webp" alt="Unblocked Games FreezeNova" width="726"
         height="90">
   </a>

   <nav class="sidebar">
      <button class="close" type="button"><svg viewBox="0 0 24 24" focusable="false"
            aria-hidden="true" class="close_svg">
            <path fill-rule="evenodd" clip-rule="evenodd"
               d="M4.29289 4.29289C4.68342 3.90237 5.31658 3.90237 5.70711 4.29289L12 10.5858L18.2929 4.29289C18.6834 3.90237 19.3166 3.90237 19.7071 4.29289C20.0976 4.68342 20.0976 5.31658 19.7071 5.70711L13.4142 12L19.7071 18.2929C20.0976 18.6834 20.0976 19.3166 19.7071 19.7071C19.3166 20.0976 18.6834 20.0976 18.2929 19.7071L12 13.4142L5.70711 19.7071C5.31658 20.0976 4.68342 20.0976 4.29289 19.7071C3.90237 19.3166 3.90237 18.6834 4.29289 18.2929L10.5858 12L4.29289 5.70711C3.90237 5.31658 3.90237 4.68342 4.29289 4.29289Z">
            </path>
         </svg></button>
      <ul class="navbar__menu">
               <li class="active">
               <a
                  href="./index.html" 
                     target="_self"
      >
                  Home
               </a>
      
         </li>
               <li>
               <a
                  href="./recently-played-games.html" 
                     target="_self"
      >
                  Recently Played
               </a>
      
         </li>
               <li>
               <a
                  href="./new-games.html" 
                     target="_self"
      >
                  New
               </a>
      
         </li>
               <li>
               <a
                  href="./2-player/index.html" 
                     target="_self"
      >
                  2 Player
               </a>
      
         </li>
               <li>
               <a
                  href="./2d/index.html" 
                     target="_self"
      >
                  2D
               </a>
      
         </li>
               <li>
               <a
                  href="./3d/index.html" 
                     target="_self"
      >
                  3D
               </a>
      
         </li>
               <li>
               <a
                  href="./action/index.html" 
                     target="_self"
      >
                  Action
               </a>
      
         </li>
               <li>
               <a
                  href="./adventure/index.html" 
                     target="_self"
      >
                  Adventure
               </a>
      
         </li>
               <li>
               <a
                  href="./arcade/index.html" 
                     target="_self"
      >
                  Arcade
               </a>
      
         </li>
               <li>
               <a
                  href="./car/index.html" 
                     target="_self"
      >
                  Car
               </a>
      
         </li>
               <li>
               <a
                  href="./clicker/index.html" 
                     target="_self"
      >
                  Clicker
               </a>
      
         </li>
               <li>
               <a
                  href="./crazy/index.html" 
                     target="_self"
      >
                  Crazy
               </a>
      
         </li>
               <li>
               <a
                  href="./drift/index.html" 
                     target="_self"
      >
                  Drift
               </a>
      
         </li>
               <li>
               <a
                  href="./driving/index.html" 
                     target="_self"
      >
                  Driving
               </a>
      
         </li>
               <li>
               <a
                  href="./girl/index.html" 
                     target="_self"
      >
                  Girl
               </a>
      
         </li>
               <li>
               <a
                  href="./io-games/index.html" 
                     target="_self"
      >
                  io Games
               </a>
      
         </li>
               <li>
               <a
                  href="./kids/index.html" 
                     target="_self"
      >
                  Kids
               </a>
      
         </li>
               <li>
               <a
                  href="./minecraft/index.html" 
                     target="_self"
      >
                  Minecraft
               </a>
      
         </li>
               <li>
               <a
                  href="./mobile/index.html" 
                     target="_self"
      >
                  Mobile
               </a>
      
         </li>
               <li>
               <a
                  href="./multiplayer/index.html" 
                     target="_self"
      >
                  Multiplayer
               </a>
      
         </li>
               <li>
               <a
                  href="./pixel/index.html" 
                     target="_self"
      >
                  Pixel
               </a>
      
         </li>
               <li>
               <a
                  href="./puzzle/index.html" 
                     target="_self"
      >
                  Puzzle
               </a>
      
         </li>
               <li>
               <a
                  href="./racing/index.html" 
                     target="_self"
      >
                  Racing
               </a>
      
         </li>
               <li>
               <a
                  href="./shooting/index.html" 
                     target="_self"
      >
                  Shooting
               </a>
      
         </li>
               <li>
               <a
                  href="./simulator/index.html" 
                     target="_self"
      >
                  Simulator
               </a>
      
         </li>
               <li>
               <a
                  href="./sniper/index.html" 
                     target="_self"
      >
                  Sniper
               </a>
      
         </li>
               <li>
               <a
                  href="./sports/index.html" 
                     target="_self"
      >
                  Sports
               </a>
      
         </li>
               <li>
               <a
                  href="./strategy/index.html" 
                     target="_self"
      >
                  Strategy
               </a>
      
         </li>
               <li>
               <a
                  href="https://freezenova.blog" 
                     target="_self"
      >
                  Subscribe
               </a>
      
         </li>
      </ul>   </nav>

   <div class="search">
      <div class="search__overlay">
         <form action="#search" class="search__form">
			<input
			class="search__input"
			type="search"
			placeholder="Search" 
			aria-label="Search" />
			
			<button 
				type="submit" 
				class="search__button">
				<span>
			   		Search
			   	</span>
			</button>
			
		</form>
      </div>
      <a href="https://www.youtube.com/@freezenova" target="_blank" class="youtube-btn"><svg xmlns="http://www.w3.org/2000/svg" width="24" viewBox="0 0 18 18" height="24" version="1.0"><defs><clipPath id="a"><path d="M0.29 0h17.419v17.419H0.29Zm0 0"/></clipPath><clipPath id="b"><path d="M9 0C4.19 0 0.29 3.9 0.29 8.71S4.19 17.418 9 17.418s8.71 -3.9 8.71 -8.709S13.81 0 9 0m0 0"/></clipPath><clipPath id="c"><path d="M5.63 4.329h8.016v8.777H5.629Zm0 0"/></clipPath><clipPath id="d"><path d="m12.984 9.79 -5.465 3.122a1.26 1.26 0 0 1 -1.261 -0.002 1.266 1.266 0 0 1 -0.628 -1.095V5.604a1.262 1.262 0 0 1 1.889 -1.097l5.466 3.122a1.248 1.248 0 0 1 0.626 1.08c0 0.448 -0.239 0.86 -0.626 1.081m0 0"/></clipPath></defs><g clip-path="url(#a)"><g clip-path="url(#b)"><path fill="none" d="M9 0C4.19 0 0.29 3.9 0.29 8.71S4.19 17.418 9 17.418s8.71 -3.9 8.71 -8.709S13.81 0 9 0Zm0 0" stroke="#fff" stroke-width="2.613"/></g></g><g clip-path="url(#c)"><g clip-path="url(#d)"><path fill="#fff" d="M14.874 3.426v10.583H5.629V3.426Zm0 0"/></g></g></svg></a>
      <!--      <button class="search__btn js-search-btn" aria-label="Search">
         <svg role="presentation" focusable="false" height="18" width="18">
            <use xlink:href="./assets/svg/svg-map.svg#search" />
         </svg>
      </button>-->
   </div>

</header>   <main class="main">

      <link rel='stylesheet' href='./assets/styles/main.css'>
      



         <div class="main__content  wrapper">
            
               <div class="section recently">
                  <div class="l-isotope js-infinitescroll">
                   <div class="grid-sizer"></div>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/664/basket-random-pro.webp"
                                                srcset="./media/posts/664/responsive/basket-random-pro-xs.webp 384w ,./media/posts/664/responsive/basket-random-pro-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Basket Random Pro Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./basket-random-pro.html">
                                          Basket Random Pro
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./2-player/index.html" class="c-card__tag">2 Player</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/665/mahjong.webp"
                                                srcset="./media/posts/665/responsive/mahjong-xs.webp 384w ,./media/posts/665/responsive/mahjong-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Mahjong Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./mahjong.html">
                                          Mahjong
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/663/conquer-kingdoms.webp"
                                                srcset="./media/posts/663/responsive/conquer-kingdoms-xs.webp 384w ,./media/posts/663/responsive/conquer-kingdoms-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Conquer Kingdoms Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./conquer-kingdoms.html">
                                          Conquer Kingdoms
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./strategy/index.html" class="c-card__tag">Strategy</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/648/monster-survivors.webp"
                                                srcset="./media/posts/648/responsive/monster-survivors-xs.webp 384w ,./media/posts/648/responsive/monster-survivors-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Monster Survivors Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./monster-survivors.html">
                                          Monster Survivors
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./action/index.html" class="c-card__tag">Action</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/658/supermarket-simulator.webp"
                                                srcset="./media/posts/658/responsive/supermarket-simulator-xs.webp 384w ,./media/posts/658/responsive/supermarket-simulator-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Supermarket Simulator Online Game">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./supermarket-simulator.html">
                                          Supermarket Simulator
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./simulator/index.html" class="c-card__tag">Simulator</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/660/mafia-getaway-cars.webp"
                                                srcset="./media/posts/660/responsive/mafia-getaway-cars-xs.webp 384w ,./media/posts/660/responsive/mafia-getaway-cars-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Mafia Getaway Cars Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./mafia-getaway-cars.html">
                                          Mafia Getaway Cars
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./driving/index.html" class="c-card__tag">Driving</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/656/spartahoppers.webp"
                                                srcset="./media/posts/656/responsive/spartahoppers-xs.webp 384w ,./media/posts/656/responsive/spartahoppers-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="SpartaHoppers Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./spartahoppers.html">
                                          SpartaHoppers
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./action/index.html" class="c-card__tag">Action</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/655/kings-io.webp"
                                                srcset="./media/posts/655/responsive/kings-io-xs.webp 384w ,./media/posts/655/responsive/kings-io-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Kings io Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./kings-io.html">
                                          Kings io
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./strategy/index.html" class="c-card__tag">Strategy</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/645/wordle-game.webp"
                                                srcset="./media/posts/645/responsive/wordle-game-xs.webp 384w ,./media/posts/645/responsive/wordle-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Wordle Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./wordle.html">
                                          Wordle
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/650/tank-arena.webp"
                                                srcset="./media/posts/650/responsive/tank-arena-xs.webp 384w ,./media/posts/650/responsive/tank-arena-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Tank Arena Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./tank-arena.html">
                                          Tank Arena
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./tank/index.html" class="c-card__tag">Tank</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/659/bolts-puzzle.webp"
                                                srcset="./media/posts/659/responsive/bolts-puzzle-xs.webp 384w ,./media/posts/659/responsive/bolts-puzzle-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Nuts and Bolts Puzzle Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./nuts-and-bolts-puzzle.html">
                                          Nuts and Bolts Puzzle
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/644/sudoku-game.webp"
                                                srcset="./media/posts/644/responsive/sudoku-game-xs.webp 384w ,./media/posts/644/responsive/sudoku-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Sudoku Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./sudoku.html">
                                          Sudoku
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/651/papas-sushiria.webp"
                                                srcset="./media/posts/651/responsive/papas-sushiria-xs.webp 384w ,./media/posts/651/responsive/papas-sushiria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Sushiria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-sushiria.html">
                                          Papa&#x27;s Sushiria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/652/escaping-the-prison.webp"
                                                srcset="./media/posts/652/responsive/escaping-the-prison-xs.webp 384w ,./media/posts/652/responsive/escaping-the-prison-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Escaping The Prison Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./escaping-the-prison.html">
                                          Escaping The Prison
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/661/hot-doggeria.webp"
                                                srcset="./media/posts/661/responsive/hot-doggeria-xs.webp 384w ,./media/posts/661/responsive/hot-doggeria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Hot Doggeria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-hot-doggeria.html">
                                          Papa&#x27;s Hot Doggeria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/643/find-it.webp"
                                                srcset="./media/posts/643/responsive/find-it-xs.webp 384w ,./media/posts/643/responsive/find-it-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Find It Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./find-it.html">
                                          Find It
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/647/papas-pizzeria.webp"
                                                srcset="./media/posts/647/responsive/papas-pizzeria-xs.webp 384w ,./media/posts/647/responsive/papas-pizzeria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Pizzeria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-pizzeria.html">
                                          Papa&#x27;s Pizzeria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/654/stealing-the-diamond.webp"
                                                srcset="./media/posts/654/responsive/stealing-the-diamond-xs.webp 384w ,./media/posts/654/responsive/stealing-the-diamond-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Stealing The Diamond Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./stealing-the-diamond.html">
                                          Stealing The Diamond
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/649/freeing-the-complex.webp"
                                                srcset="./media/posts/649/responsive/freeing-the-complex-xs.webp 384w ,./media/posts/649/responsive/freeing-the-complex-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Fleeing the Complex Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./fleeing-the-complex.html">
                                          Fleeing the Complex
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/653/infiltrating-the-airship.webp"
                                                srcset="./media/posts/653/responsive/infiltrating-the-airship-xs.webp 384w ,./media/posts/653/responsive/infiltrating-the-airship-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Infiltrating The Airship Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./infiltrating-the-airship.html">
                                          Infiltrating The Airship
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/662/donuteria.webp"
                                                srcset="./media/posts/662/responsive/donuteria-xs.webp 384w ,./media/posts/662/responsive/donuteria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Donuteria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-donuteria.html">
                                          Papa&#x27;s Donuteria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/642/tile-match.webp"
                                                srcset="./media/posts/642/responsive/tile-match-xs.webp 384w ,./media/posts/642/responsive/tile-match-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Tile Match Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./tile-match.html">
                                          Tile Match
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/657/breaking-the-bank.webp"
                                                srcset="./media/posts/657/responsive/breaking-the-bank-xs.webp 384w ,./media/posts/657/responsive/breaking-the-bank-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Breaking The Bank Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./breaking-the-bank.html">
                                          Breaking The Bank
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/641/watermelon-game-512.webp"
                                                srcset="./media/posts/641/responsive/watermelon-game-512-xs.webp 384w ,./media/posts/641/responsive/watermelon-game-512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Watermelon Game Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./watermelon-game.html">
                                          Watermelon Game
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./arcade/index.html" class="c-card__tag">Arcade</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/635/snake-game.webp"
                                                srcset="./media/posts/635/responsive/snake-game-xs.webp 384w ,./media/posts/635/responsive/snake-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Snake Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./snake.html">
                                          Snake
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./snake/index.html" class="c-card__tag">Snake</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/61/2048-game.webp"
                                                srcset="./media/posts/61/responsive/2048-game-xs.webp 384w ,./media/posts/61/responsive/2048-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="2048 Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./2048.html">
                                          2048
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/637/sprunki-game.webp"
                                                srcset="./media/posts/637/responsive/sprunki-game-xs.webp 384w ,./media/posts/637/responsive/sprunki-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Sprunki Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./sprunki.html">
                                          Sprunki
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./2d/index.html" class="c-card__tag">2D</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/634/stickman-city-512.webp"
                                                srcset="./media/posts/634/responsive/stickman-city-512-xs.webp 384w ,./media/posts/634/responsive/stickman-city-512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Stickman GTA City Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./stickman-gta-city.html">
                                          Stickman GTA City
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./simulator/index.html" class="c-card__tag">Simulator</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/639/fnf-garcello.webp"
                                                srcset="./media/posts/639/responsive/fnf-garcello-xs.webp 384w ,./media/posts/639/responsive/fnf-garcello-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="FNF Garcello Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./fnf-garcello.html">
                                          FNF Garcello
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./2d/index.html" class="c-card__tag">2D</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/640/voxel-world.webp"
                                                srcset="./media/posts/640/responsive/voxel-world-xs.webp 384w ,./media/posts/640/responsive/voxel-world-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Voxel World Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./voxel-world.html">
                                          Voxel World
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./adventure/index.html" class="c-card__tag">Adventure</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/625/survival-karts.webp"
                                                srcset="./media/posts/625/responsive/survival-karts-xs.webp 384w ,./media/posts/625/responsive/survival-karts-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Survival Karts Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./survival-karts.html">
                                          Survival Karts
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./crazy/index.html" class="c-card__tag">Crazy</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/619/block-blast.webp"
                                                srcset="./media/posts/619/responsive/block-blast-xs.webp 384w ,./media/posts/619/responsive/block-blast-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Block Blast Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./block-blast.html">
                                          Block Blast
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/412/ovo-512.jpg"
                                                srcset="./media/posts/412/responsive/ovo-512-xs.jpg 384w ,./media/posts/412/responsive/ovo-512-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="OvO Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./ovo.html">
                                          OvO
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./escape/index.html" class="c-card__tag">Escape</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/449/Basketball-Stars-512x512.jpg"
                                                srcset="./media/posts/449/responsive/Basketball-Stars-512x512-xs.jpg 384w ,./media/posts/449/responsive/Basketball-Stars-512x512-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Basketball Stars Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./basketball-stars.html">
                                          Basketball Stars
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./basketball/index.html" class="c-card__tag">Basketball</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/448/Moto-X3M-Original-512x512.jpg"
                                                srcset="./media/posts/448/responsive/Moto-X3M-Original-512x512-xs.jpg 384w ,./media/posts/448/responsive/Moto-X3M-Original-512x512-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Moto X3M Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./moto-x3m.html">
                                          Moto X3M
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./bike/index.html" class="c-card__tag">Bike</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/646/shadow-strike-game.webp"
                                                srcset="./media/posts/646/responsive/shadow-strike-game-xs.webp 384w ,./media/posts/646/responsive/shadow-strike-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Shadow Strike Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./shadow-strike.html">
                                          Shadow Strike
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./action/index.html" class="c-card__tag">Action</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/363/drift_boss_unblocked_512.jpg"
                                                srcset="./media/posts/363/responsive/drift_boss_unblocked_512-xs.jpg 384w ,./media/posts/363/responsive/drift_boss_unblocked_512-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Drift Boss Unblocked Game">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./drift-boss.html">
                                          Drift Boss
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./drift/index.html" class="c-card__tag">Drift</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/443/drift-hunters-game.jpg"
                                                srcset="./media/posts/443/responsive/drift-hunters-game-xs.jpg 384w ,./media/posts/443/responsive/drift-hunters-game-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Drift Hunters Unblocked Game">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./drift-hunters.html">
                                          Drift Hunters
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./drift/index.html" class="c-card__tag">Drift</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/598/super-car-driving-game.webp"
                                                srcset="./media/posts/598/responsive/super-car-driving-game-xs.webp 384w ,./media/posts/598/responsive/super-car-driving-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Super Car Driving Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./super-car-driving.html">
                                          Super Car Driving
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./driving/index.html" class="c-card__tag">Driving</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/614/warstrike-icon.webp"
                                                srcset="./media/posts/614/responsive/warstrike-icon-xs.webp 384w ,./media/posts/614/responsive/warstrike-icon-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="WarStrike Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./warstrike.html">
                                          WarStrike
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./shooting/index.html" class="c-card__tag">Shooting</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/636/papas-scooperia.webp"
                                                srcset="./media/posts/636/responsive/papas-scooperia-xs.webp 384w ,./media/posts/636/responsive/papas-scooperia-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Scooperia Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-scooperia.html">
                                          Papa&#x27;s Scooperia
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/633/bffs-black-friday-collection.webp"
                                                srcset="./media/posts/633/responsive/bffs-black-friday-collection-xs.webp 384w ,./media/posts/633/responsive/bffs-black-friday-collection-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="BFFs Black Friday Collection Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./bffs-black-friday-collection.html">
                                          BFFs Black Friday Collection
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./girl/index.html" class="c-card__tag">Girl</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/632/bffs-retro-time-travel-fashion.webp"
                                                srcset="./media/posts/632/responsive/bffs-retro-time-travel-fashion-xs.webp 384w ,./media/posts/632/responsive/bffs-retro-time-travel-fashion-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Bffs Retro Time Travel Fashion Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./bffs-retro-time-travel-fashion.html">
                                          Bffs Retro Time Travel Fashion
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./girl/index.html" class="c-card__tag">Girl</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/628/cactus-mccoy-2-game.webp"
                                                srcset="./media/posts/628/responsive/cactus-mccoy-2-game-xs.webp 384w ,./media/posts/628/responsive/cactus-mccoy-2-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Cactus McCoy 2 Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./cactus-mccoy-2.html">
                                          Cactus McCoy 2
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/624/cake-match-puzzle.webp"
                                                srcset="./media/posts/624/responsive/cake-match-puzzle-xs.webp 384w ,./media/posts/624/responsive/cake-match-puzzle-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Cake Match Puzzle Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./cake-match-puzzle.html">
                                          Cake Match Puzzle
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/622/cubeshot-io.webp"
                                                srcset="./media/posts/622/responsive/cubeshot-io-xs.webp 384w ,./media/posts/622/responsive/cubeshot-io-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Cubeshot io Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./cubeshot-io.html">
                                          Cubeshot io
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./io-games/index.html" class="c-card__tag">io Games</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/621/basketball-king.webp"
                                                srcset="./media/posts/621/responsive/basketball-king-xs.webp 384w ,./media/posts/621/responsive/basketball-king-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Basketball King Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./basketball-king.html">
                                          Basketball King
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./2-player/index.html" class="c-card__tag">2 Player</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/620/papas-taco-mia.webp"
                                                srcset="./media/posts/620/responsive/papas-taco-mia-xs.webp 384w ,./media/posts/620/responsive/papas-taco-mia-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Taco Mia Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-taco-mia.html">
                                          Papa&#x27;s Taco Mia
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/618/papas-pastaria.webp"
                                                srcset="./media/posts/618/responsive/papas-pastaria-xs.webp 384w ,./media/posts/618/responsive/papas-pastaria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Pastaria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-pastaria.html">
                                          Papa&#x27;s Pastaria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/617/soccer-random-pro.webp"
                                                srcset="./media/posts/617/responsive/soccer-random-pro-xs.webp 384w ,./media/posts/617/responsive/soccer-random-pro-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Soccer Random Pro Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./soccer-random-pro.html">
                                          Soccer Random Pro
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./2-player/index.html" class="c-card__tag">2 Player</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/616/papas-wingeria.webp"
                                                srcset="./media/posts/616/responsive/papas-wingeria-xs.webp 384w ,./media/posts/616/responsive/papas-wingeria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Wingeria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-wingeria.html">
                                          Papa&#x27;s Wingeria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/615/geometry-escape.webp"
                                                srcset="./media/posts/615/responsive/geometry-escape-xs.webp 384w ,./media/posts/615/responsive/geometry-escape-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Geometry Escape Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./geometry-escape.html">
                                          Geometry Escape
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./escape/index.html" class="c-card__tag">Escape</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/579/battle-royale-2d.webp"
                                                srcset="./media/posts/579/responsive/battle-royale-2d-xs.webp 384w ,./media/posts/579/responsive/battle-royale-2d-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Su Battle Royale Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./su-battle-royale.html">
                                          Su Battle Royale
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./io-games/index.html" class="c-card__tag">io Games</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/613/papas-burgeria.webp"
                                                srcset="./media/posts/613/responsive/papas-burgeria-xs.webp 384w ,./media/posts/613/responsive/papas-burgeria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Burgeria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-burgeria.html">
                                          Papa&#x27;s Burgeria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/612/papas-cupcakeria.webp"
                                                srcset="./media/posts/612/responsive/papas-cupcakeria-xs.webp 384w ,./media/posts/612/responsive/papas-cupcakeria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Cupcakeria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-cupcakeria.html">
                                          Papa&#x27;s Cupcakeria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/611/papas-freezeria.webp"
                                                srcset="./media/posts/611/responsive/papas-freezeria-xs.webp 384w ,./media/posts/611/responsive/papas-freezeria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Freezeria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-freezeria.html">
                                          Papa&#x27;s Freezeria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/610/mega-soccer-game512.webp"
                                                srcset="./media/posts/610/responsive/mega-soccer-game512-xs.webp 384w ,./media/posts/610/responsive/mega-soccer-game512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Mega Soccer Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./mega-soccer.html">
                                          Mega Soccer
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./sports/index.html" class="c-card__tag">Sports</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/75/rebel-forces.jpg"
                                                srcset="./media/posts/75/responsive/rebel-forces-xs.jpg 384w ,./media/posts/75/responsive/rebel-forces-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Rebel Forces Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./rebel-forces.html">
                                          Rebel Forces
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./shooting/index.html" class="c-card__tag">Shooting</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/630/surviv-bros.webp"
                                                srcset="./media/posts/630/responsive/surviv-bros-xs.webp 384w ,./media/posts/630/responsive/surviv-bros-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Surviv Bros Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./surviv-bros.html">
                                          Surviv Bros
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./io-games/index.html" class="c-card__tag">io Games</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/607/bookworm.webp"
                                                srcset="./media/posts/607/responsive/bookworm-xs.webp 384w ,./media/posts/607/responsive/bookworm-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Bookworm Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./bookworm.html">
                                          Bookworm
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/605/fnaf-4-game.webp"
                                                srcset="./media/posts/605/responsive/fnaf-4-game-xs.webp 384w ,./media/posts/605/responsive/fnaf-4-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="FNAF 4 Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./fnaf-4.html">
                                          FNAF 4
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./scary/index.html" class="c-card__tag">Scary</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/604/axis-football-league-game.webp"
                                                srcset="./media/posts/604/responsive/axis-football-league-game-xs.webp 384w ,./media/posts/604/responsive/axis-football-league-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Axis Football League Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./axis-football-league.html">
                                          Axis Football League
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/596/troll-level-game.webp"
                                                srcset="./media/posts/596/responsive/troll-level-game-xs.webp 384w ,./media/posts/596/responsive/troll-level-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Troll Level Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./troll-level.html">
                                          Troll Level
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./escape/index.html" class="c-card__tag">Escape</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/603/papas-cheeseria.webp"
                                                srcset="./media/posts/603/responsive/papas-cheeseria-xs.webp 384w ,./media/posts/603/responsive/papas-cheeseria-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Papa&#x27;s Cheeseria Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./papas-cheeseria.html">
                                          Papa&#x27;s Cheeseria
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/602/domino-solitaire-512.webp"
                                                srcset="./media/posts/602/responsive/domino-solitaire-512-xs.webp 384w ,./media/posts/602/responsive/domino-solitaire-512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Domino Solitaire Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./domino-solitaire.html">
                                          Domino Solitaire
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./puzzle/index.html" class="c-card__tag">Puzzle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/601/cactus-mccoy-1.webp"
                                                srcset="./media/posts/601/responsive/cactus-mccoy-1-xs.webp 384w ,./media/posts/601/responsive/cactus-mccoy-1-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Cactus McCoy 1 Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./cactus-mccoy-1.html">
                                          Cactus McCoy 1
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/600/fnaf-3.webp"
                                                srcset="./media/posts/600/responsive/fnaf-3-xs.webp 384w ,./media/posts/600/responsive/fnaf-3-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="FNAF 3 Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./fnaf-3.html">
                                          FNAF 3
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./scary/index.html" class="c-card__tag">Scary</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/599/jacksmith-512.webp"
                                                srcset="./media/posts/599/responsive/jacksmith-512-xs.webp 384w ,./media/posts/599/responsive/jacksmith-512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Jacksmith Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./jacksmith.html">
                                          Jacksmith
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./flash/index.html" class="c-card__tag">Flash</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/496/idle-breakout.webp"
                                                srcset="./media/posts/496/responsive/idle-breakout-xs.webp 384w ,./media/posts/496/responsive/idle-breakout-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Idle Breakout Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./idle-breakout.html">
                                          Idle Breakout
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./clicker/index.html" class="c-card__tag">Clicker</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/592/a-small-world-cup-512.webp"
                                                srcset="./media/posts/592/responsive/a-small-world-cup-512-xs.webp 384w ,./media/posts/592/responsive/a-small-world-cup-512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="A Small World Cup Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./a-small-world-cup.html">
                                          A Small World Cup
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./sports/index.html" class="c-card__tag">Sports</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/444/drift-hunters-2024-freezenova.jpg"
                                                srcset="./media/posts/444/responsive/drift-hunters-2024-freezenova-xs.jpg 384w ,./media/posts/444/responsive/drift-hunters-2024-freezenova-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Drift Hunters 2024 Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./drift-hunters-2024.html">
                                          Drift Hunters 2024
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./drift/index.html" class="c-card__tag">Drift</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/597/fnaf-2-game.webp"
                                                srcset="./media/posts/597/responsive/fnaf-2-game-xs.webp 384w ,./media/posts/597/responsive/fnaf-2-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="FNAF 2 Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./fnaf-2.html">
                                          FNAF 2
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./scary/index.html" class="c-card__tag">Scary</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/32/HighwayTraffic512.jpg"
                                                srcset="./media/posts/32/responsive/HighwayTraffic512-xs.jpg 384w ,./media/posts/32/responsive/HighwayTraffic512-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Highway Traffic Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./highway-traffic.html">
                                          Highway Traffic
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./car/index.html" class="c-card__tag">Car</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/594/fnaf-512.webp"
                                                srcset="./media/posts/594/responsive/fnaf-512-xs.webp 384w ,./media/posts/594/responsive/fnaf-512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="FNAF Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./fnaf.html">
                                          FNAF
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./scary/index.html" class="c-card__tag">Scary</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/406/tap-tap-shots-512.jpg"
                                                srcset="./media/posts/406/responsive/tap-tap-shots-512-xs.jpg 384w ,./media/posts/406/responsive/tap-tap-shots-512-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Tap Tap Shots Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./tap-tap-shots.html">
                                          Tap Tap Shots
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./sports/index.html" class="c-card__tag">Sports</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/372/idle-mining-empire-512.jpg"
                                                srcset="./media/posts/372/responsive/idle-mining-empire-512-xs.jpg 384w ,./media/posts/372/responsive/idle-mining-empire-512-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Idle Mining Empire Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./idle-mining-empire.html">
                                          Idle Mining Empire
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./idle/index.html" class="c-card__tag">Idle</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/521/Football-Legends-game.webp"
                                                srcset="./media/posts/521/responsive/Football-Legends-game-xs.webp 384w ,./media/posts/521/responsive/Football-Legends-game-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Football Legends Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./football-legends.html">
                                          Football Legends
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./sports/index.html" class="c-card__tag">Sports</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/589/highway-driver-512.webp"
                                                srcset="./media/posts/589/responsive/highway-driver-512-xs.webp 384w ,./media/posts/589/responsive/highway-driver-512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Highway Driver Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./highway-driver.html">
                                          Highway Driver
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./driving/index.html" class="c-card__tag">Driving</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/152/test.jpg"
                                                srcset="./media/posts/152/responsive/test-xs.jpg 384w ,./media/posts/152/responsive/test-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Love Tester Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./love-tester.html">
                                          Love Tester
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./2d/index.html" class="c-card__tag">2D</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/335/512.jpg"
                                                srcset="./media/posts/335/responsive/512-xs.jpg 384w ,./media/posts/335/responsive/512-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Real Flight Simulator Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./real-flight-simulator.html">
                                          Real Flight Simulator
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./simulator/index.html" class="c-card__tag">Simulator</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/57/stickman.jpg"
                                                srcset="./media/posts/57/responsive/stickman-xs.jpg 384w ,./media/posts/57/responsive/stickman-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Stickman Ragdoll Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./stickman-ragdoll.html">
                                          Stickman Ragdoll
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./arcade/index.html" class="c-card__tag">Arcade</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/568/basket-hoop-512.webp"
                                                srcset="./media/posts/568/responsive/basket-hoop-512-xs.webp 384w ,./media/posts/568/responsive/basket-hoop-512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Basket Hoop Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./basket-hoop.html">
                                          Basket Hoop
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./sports/index.html" class="c-card__tag">Sports</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/155/512.jpg"
                                                srcset="./media/posts/155/responsive/512-xs.jpg 384w ,./media/posts/155/responsive/512-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Police Chase Drifter Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./police-chase-drifter.html">
                                          Police Chase Drifter
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./driving/index.html" class="c-card__tag">Driving</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/233/512-2.jpg"
                                                srcset="./media/posts/233/responsive/512-2-xs.jpg 384w ,./media/posts/233/responsive/512-2-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Stickman Destruction Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./stickman-destruction.html">
                                          Stickman Destruction
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./simulator/index.html" class="c-card__tag">Simulator</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/436/paper-io-unblocked.jpg"
                                                srcset="./media/posts/436/responsive/paper-io-unblocked-xs.jpg 384w ,./media/posts/436/responsive/paper-io-unblocked-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Paper IO Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./paper-io.html">
                                          Paper IO
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./io-games/index.html" class="c-card__tag">io Games</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/528/gigga-io.webp"
                                                srcset="./media/posts/528/responsive/gigga-io-xs.webp 384w ,./media/posts/528/responsive/gigga-io-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Gigga.io Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./gigga-io.html">
                                          Gigga io
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./io-games/index.html" class="c-card__tag">io Games</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/428/drift-rider.jpg"
                                                srcset="./media/posts/428/responsive/drift-rider-xs.jpg 384w ,./media/posts/428/responsive/drift-rider-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Drift Rider Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./drift-rider.html">
                                          Drift Rider
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./drift/index.html" class="c-card__tag">Drift</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/310/512-2.jpg"
                                                srcset="./media/posts/310/responsive/512-2-xs.jpg 384w ,./media/posts/310/responsive/512-2-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Masked Special Forces Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./masked-special-forces.html">
                                          Masked Special Forces
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./shooting/index.html" class="c-card__tag">Shooting</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/573/stickman-parkour-512.webp"
                                                srcset="./media/posts/573/responsive/stickman-parkour-512-xs.webp 384w ,./media/posts/573/responsive/stickman-parkour-512-sm.webp 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="Stickman Parkour Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./stickman-parkour.html">
                                          Stickman Parkour
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./escape/index.html" class="c-card__tag">Escape</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                        <article
                           class="c-card">
                           <div class="c-card__wrapper">
                                       <figure class="c-card__image ">
                                          <img
                                             src="./media/posts/365/gta-simulator.jpg"
                                                srcset="./media/posts/365/responsive/gta-simulator-xs.jpg 384w ,./media/posts/365/responsive/gta-simulator-sm.jpg 600w" sizes="(min-width: 600px) 14.285vw, 100vw"
                                              loading="lazy"
                                             height="512"
                                             width="512"
                                             alt="GTA Simulator Unblocked">
                                       </figure>
                              <div class="c-card__content">
                                 <header>
                                    <div class="c-card__title">
                                       <a href="./gta-simulator.html">
                                          GTA Simulator
                                       </a>
                                    </div>
                                 </header>
                                    <footer class="c-card__meta">
                                             <a href="./simulator/index.html" class="c-card__tag">Simulator</a>
                                    </footer>
                              </div>
                           </div>
                        </article>
                  </div>
               </div>
         </div>
          <nav class="pagination">
                  <span
                      class="pagination-first pagination-inactive"> &#8249;
                      Previous
                  </span>
              <div>
                          <a href="#" class="pagination-active">
                              1
                          </a>
                          <a href="./page/2/index.html">
                              2
                          </a>
                          <a href="./page/3/index.html">
                              3
                          </a>
                          <a href="./page/4/index.html">
                              4
                          </a>
                          <a href="./page/5/index.html">
                              5
                          </a>
                          <a href="./page/6/index.html">
                              6
                          </a>
                          <a href="./page/7/index.html">
                              7
                          </a>
                          <a href="./page/8/index.html">
                              8
                          </a>
              </div>
                  <a
                      href="./page/2/index.html"
                       class="pagination__next">
                      Next
                       &#8250;
                  </a>
          </nav>
      
                  <button class="view-more">View more</button>   
   </div>
   
   
   <br>

<a id="recentGamesLabel" href="/recently-played-games.html" style="display: none; color: white; font-weight: bold;">Continue playing</a>
<div id="recentGamesHorizontalCon" class="horizontalCon">

	<div class="arrowsCon">
		<div class="arrowCon arrowLeftCon" id="arrowLeft" style="visibility: hidden;">
			<img class="arrow" src="/assets/images/icons/arrow-left.svg">
		</div>
		
		<div class="arrowCon arrowRightCon" id="arrowRight" style="visibility: hidden;">
			<img class="arrow" src="/assets/images/icons/arrow-right.svg">
		</div>
	</div>

</div>
<br>


   <div id='gamesList'></div>
<a id="GamesLabel" href="/car/index.html" style="color: white; font-weight: bold; padding-left: 4%;">Car Games</a>
	<div id="GamesHorizontalCon" class="horizontalCon"><div class="arrowsCon">
			<div class="arrowCon arrowLeftCon" id="arrowLeft" style="visibility: hidden;">
				<img class="arrow" src="/assets/images/icons/arrow-left.svg">
			</div>
			
			<div class="arrowCon arrowRightCon" id="arrowRight" style="visibility: visible;">
				<img class="arrow" src="/assets/images/icons/arrow-right.svg">
			</div>
		</div><div class="gamesCon"><div tagname="Mafia Getaway Cars" id="gameDiv" onclick="location.href='/mafia-getaway-cars.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/660/responsive/mafia-getaway-cars-xs.webp" alt="FreezeNova Mafia Getaway Cars" title="FreezeNova Mafia Getaway Cars" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Mafia Getaway Cars</h3>
</div><div tagname="Stickman GTA City" id="gameDiv" onclick="location.href='/stickman-gta-city.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/634/responsive/stickman-city-512-xs.webp" alt="FreezeNova Stickman GTA City" title="FreezeNova Stickman GTA City" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Stickman GTA City</h3>
</div><div tagname="Survival Karts" id="gameDiv" onclick="location.href='/survival-karts.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/625/responsive/survival-karts-xs.webp" alt="FreezeNova Survival Karts" title="FreezeNova Survival Karts" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Survival Karts</h3>
</div><div tagname="Drift Boss" id="gameDiv" onclick="location.href='/drift-boss.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/363/responsive/drift_boss_unblocked_512-xs.jpg" alt="FreezeNova Drift Boss" title="FreezeNova Drift Boss" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Drift Boss</h3>
</div><div tagname="Drift Hunters" id="gameDiv" onclick="location.href='/drift-hunters.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/443/responsive/drift-hunters-game-xs.jpg" alt="FreezeNova Drift Hunters" title="FreezeNova Drift Hunters" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Drift Hunters</h3>
</div><div tagname="Super Car Driving" id="gameDiv" onclick="location.href='/super-car-driving.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/598/responsive/super-car-driving-game-xs.webp" alt="FreezeNova Super Car Driving" title="FreezeNova Super Car Driving" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Super Car Driving</h3>
</div><div tagname="Drift Hunters 2024" id="gameDiv" onclick="location.href='/drift-hunters-2024.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/444/responsive/drift-hunters-2024-freezenova-xs.jpg" alt="FreezeNova Drift Hunters 2024" title="FreezeNova Drift Hunters 2024" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Drift Hunters 2024</h3>
</div><div tagname="Highway Traffic" id="gameDiv" onclick="location.href='/highway-traffic.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/32/responsive/HighwayTraffic512-xs.jpg" alt="FreezeNova Highway Traffic" title="FreezeNova Highway Traffic" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Highway Traffic</h3>
</div><div tagname="Highway Driver" id="gameDiv" onclick="location.href='/highway-driver.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/589/responsive/highway-driver-512-xs.webp" alt="FreezeNova Highway Driver" title="FreezeNova Highway Driver" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Highway Driver</h3>
</div><div tagname="Police Chase Drifter" id="gameDiv" onclick="location.href='/police-chase-drifter.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/155/responsive/512-xs.jpg" alt="FreezeNova Police Chase Drifter" title="FreezeNova Police Chase Drifter" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Police Chase Drifter</h3>
</div><div tagname="Drift Rider" id="gameDiv" onclick="location.href='/drift-rider.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/428/responsive/drift-rider-xs.jpg" alt="FreezeNova Drift Rider" title="FreezeNova Drift Rider" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Drift Rider</h3>
</div><div tagname="GTA Simulator" id="gameDiv" onclick="location.href='/gta-simulator.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/365/responsive/gta-simulator-xs.jpg" alt="FreezeNova GTA Simulator" title="FreezeNova GTA Simulator" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">GTA Simulator</h3>
</div><div tagname="Car Stunt King" id="gameDiv" onclick="location.href='/car-stunt-king.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/501/responsive/car-stunt-king-xs.jpg" alt="FreezeNova Car Stunt King" title="FreezeNova Car Stunt King" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Car Stunt King</h3>
</div><div tagname="Derby Cars Arena" id="gameDiv" onclick="location.href='/derby-cars-arena.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/587/responsive/derby-cars-arena-512-xs.webp" alt="FreezeNova Derby Cars Arena" title="FreezeNova Derby Cars Arena" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Derby Cars Arena</h3>
</div></div></div><br><a id="GamesLabel" href="/action/index.html" style="color: white; font-weight: bold; padding-left: 4%;">Action Games</a>
	<div id="GamesHorizontalCon" class="horizontalCon"><div class="arrowsCon">
			<div class="arrowCon arrowLeftCon" id="arrowLeft" style="visibility: hidden;">
				<img class="arrow" src="/assets/images/icons/arrow-left.svg">
			</div>
			
			<div class="arrowCon arrowRightCon" id="arrowRight" style="visibility: visible;">
				<img class="arrow" src="/assets/images/icons/arrow-right.svg">
			</div>
		</div><div class="gamesCon"><div tagname="Monster Survivors" id="gameDiv" onclick="location.href='/monster-survivors.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/648/responsive/monster-survivors-xs.webp" alt="FreezeNova Monster Survivors" title="FreezeNova Monster Survivors" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Monster Survivors</h3>
</div><div tagname="SpartaHoppers" id="gameDiv" onclick="location.href='/spartahoppers.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/656/responsive/spartahoppers-xs.webp" alt="FreezeNova SpartaHoppers" title="FreezeNova SpartaHoppers" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">SpartaHoppers</h3>
</div><div tagname="Tank Arena" id="gameDiv" onclick="location.href='/tank-arena.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/650/responsive/tank-arena-xs.webp" alt="FreezeNova Tank Arena" title="FreezeNova Tank Arena" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Tank Arena</h3>
</div><div tagname="Shadow Strike" id="gameDiv" onclick="location.href='/shadow-strike.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/646/responsive/shadow-strike-game-xs.webp" alt="FreezeNova Shadow Strike" title="FreezeNova Shadow Strike" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Shadow Strike</h3>
</div><div tagname="WarStrike" id="gameDiv" onclick="location.href='/warstrike.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/614/responsive/warstrike-icon-xs.webp" alt="FreezeNova WarStrike" title="FreezeNova WarStrike" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">WarStrike</h3>
</div><div tagname="Cactus McCoy 2" id="gameDiv" onclick="location.href='/cactus-mccoy-2.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/628/responsive/cactus-mccoy-2-game-xs.webp" alt="FreezeNova Cactus McCoy 2" title="FreezeNova Cactus McCoy 2" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Cactus McCoy 2</h3>
</div><div tagname="Rebel Forces" id="gameDiv" onclick="location.href='/rebel-forces.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/75/responsive/rebel-forces-xs.jpg" alt="FreezeNova Rebel Forces" title="FreezeNova Rebel Forces" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Rebel Forces</h3>
</div><div tagname="Cactus McCoy 1" id="gameDiv" onclick="location.href='/cactus-mccoy-1.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/601/responsive/cactus-mccoy-1-xs.webp" alt="FreezeNova Cactus McCoy 1" title="FreezeNova Cactus McCoy 1" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Cactus McCoy 1</h3>
</div><div tagname="Masked Special Forces" id="gameDiv" onclick="location.href='/masked-special-forces.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/310/responsive/512-2-xs.jpg" alt="FreezeNova Masked Special Forces" title="FreezeNova Masked Special Forces" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Masked Special Forces</h3>
</div><div tagname="FPS Strike" id="gameDiv" onclick="location.href='/fps-strike.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/566/responsive/fps-strike-512-xs.webp" alt="FreezeNova FPS Strike" title="FreezeNova FPS Strike" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">FPS Strike</h3>
</div><div tagname="Archer Hero" id="gameDiv" onclick="location.href='/archer-hero.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/346/responsive/512-2-xs.jpg" alt="FreezeNova Archer Hero" title="FreezeNova Archer Hero" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Archer Hero</h3>
</div><div tagname="Swords and Souls" id="gameDiv" onclick="location.href='/swords-and-souls.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/584/responsive/swords-and-souls-512-xs.webp" alt="FreezeNova Swords and Souls" title="FreezeNova Swords and Souls" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Swords and Souls</h3>
</div><div tagname="ArmedForces.io" id="gameDiv" onclick="location.href='/armedforces-io.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/234/responsive/512-xs.jpg" alt="FreezeNova ArmedForces.io" title="FreezeNova ArmedForces.io" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">ArmedForces.io</h3>
</div><div tagname="ForceZ.io" id="gameDiv" onclick="location.href='/forcez-io.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/1/responsive/forceZ-xs.jpg" alt="FreezeNova ForceZ.io" title="FreezeNova ForceZ.io" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">ForceZ.io</h3>
</div></div></div><br><a id="GamesLabel" href="/2-player/index.html" style="color: white; font-weight: bold; padding-left: 4%;">2 Player Games</a>
	<div id="GamesHorizontalCon" class="horizontalCon"><div class="arrowsCon">
			<div class="arrowCon arrowLeftCon" id="arrowLeft" style="visibility: hidden;">
				<img class="arrow" src="/assets/images/icons/arrow-left.svg">
			</div>
			
			<div class="arrowCon arrowRightCon" id="arrowRight" style="visibility: visible;">
				<img class="arrow" src="/assets/images/icons/arrow-right.svg">
			</div>
		</div><div class="gamesCon"><div tagname="Basket Random Pro" id="gameDiv" onclick="location.href='/basket-random-pro.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/664/responsive/basket-random-pro-xs.webp" alt="FreezeNova Basket Random Pro" title="FreezeNova Basket Random Pro" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Basket Random Pro</h3>
</div><div tagname="Snake" id="gameDiv" onclick="location.href='/snake.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/635/responsive/snake-game-xs.webp" alt="FreezeNova Snake" title="FreezeNova Snake" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Snake</h3>
</div><div tagname="Basketball Stars" id="gameDiv" onclick="location.href='/basketball-stars.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/449/responsive/Basketball-Stars-512x512-xs.jpg" alt="FreezeNova Basketball Stars" title="FreezeNova Basketball Stars" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Basketball Stars</h3>
</div><div tagname="Basketball King" id="gameDiv" onclick="location.href='/basketball-king.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/621/responsive/basketball-king-xs.webp" alt="FreezeNova Basketball King" title="FreezeNova Basketball King" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Basketball King</h3>
</div><div tagname="Soccer Random Pro" id="gameDiv" onclick="location.href='/soccer-random-pro.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/617/responsive/soccer-random-pro-xs.webp" alt="FreezeNova Soccer Random Pro" title="FreezeNova Soccer Random Pro" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Soccer Random Pro</h3>
</div><div tagname="Football Legends" id="gameDiv" onclick="location.href='/football-legends.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/521/responsive/Football-Legends-game-xs.webp" alt="FreezeNova Football Legends" title="FreezeNova Football Legends" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Football Legends</h3>
</div><div tagname="Car Football" id="gameDiv" onclick="location.href='/car-football.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/351/responsive/car-football-unblocked-game-xs.jpg" alt="FreezeNova Car Football" title="FreezeNova Car Football" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Car Football</h3>
</div><div tagname="Get On Top" id="gameDiv" onclick="location.href='/get-on-top.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/463/responsive/get-on-top-unblocked-game-xs.jpg" alt="FreezeNova Get On Top" title="FreezeNova Get On Top" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Get On Top</h3>
</div><div tagname="Super Soccer Noggins" id="gameDiv" onclick="location.href='/super-soccer-noggins.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/524/responsive/super-soccer-noggins-xs.webp" alt="FreezeNova Super Soccer Noggins" title="FreezeNova Super Soccer Noggins" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Super Soccer Noggins</h3>
</div><div tagname="Basketball Slam Dunk" id="gameDiv" onclick="location.href='/basketball-slam-dunk.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/200/responsive/512-2-xs.jpg" alt="FreezeNova Basketball Slam Dunk" title="FreezeNova Basketball Slam Dunk" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Basketball Slam Dunk</h3>
</div><div tagname="Tennis Masters" id="gameDiv" onclick="location.href='/tennis-masters.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/454/responsive/tennis-masters-512-xs.jpg" alt="FreezeNova Tennis Masters" title="FreezeNova Tennis Masters" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Tennis Masters</h3>
</div><div tagname="12 MiniBattles" id="gameDiv" onclick="location.href='/12-minibattles.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/507/responsive/12-minibattles-xs.webp" alt="FreezeNova 12 MiniBattles" title="FreezeNova 12 MiniBattles" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">12 MiniBattles</h3>
</div><div tagname="Drunken Duel" id="gameDiv" onclick="location.href='/drunken-duel.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/464/responsive/drunken-duel-unblocked-xs.jpg" alt="FreezeNova Drunken Duel" title="FreezeNova Drunken Duel" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Drunken Duel</h3>
</div><div tagname="Bad Dolls" id="gameDiv" onclick="location.href='/bad-dolls.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/506/responsive/bad-dolls-xs.webp" alt="FreezeNova Bad Dolls" title="FreezeNova Bad Dolls" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Bad Dolls</h3>
</div></div></div><br><a id="GamesLabel" href="/io-games/index.html" style="color: white; font-weight: bold; padding-left: 4%;">IO Games</a>
	<div id="GamesHorizontalCon" class="horizontalCon"><div class="arrowsCon">
			<div class="arrowCon arrowLeftCon" id="arrowLeft" style="visibility: hidden;">
				<img class="arrow" src="/assets/images/icons/arrow-left.svg">
			</div>
			
			<div class="arrowCon arrowRightCon" id="arrowRight" style="visibility: visible;">
				<img class="arrow" src="/assets/images/icons/arrow-right.svg">
			</div>
		</div><div class="gamesCon"><div tagname="Cubeshot io" id="gameDiv" onclick="location.href='/cubeshot-io.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/622/responsive/cubeshot-io-xs.webp" alt="FreezeNova Cubeshot io" title="FreezeNova Cubeshot io" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Cubeshot io</h3>
</div><div tagname="Su Battle Royale" id="gameDiv" onclick="location.href='/su-battle-royale.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/579/responsive/battle-royale-2d-xs.webp" alt="FreezeNova Su Battle Royale" title="FreezeNova Su Battle Royale" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Su Battle Royale</h3>
</div><div tagname="Surviv Bros" id="gameDiv" onclick="location.href='/surviv-bros.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/630/responsive/surviv-bros-xs.webp" alt="FreezeNova Surviv Bros" title="FreezeNova Surviv Bros" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Surviv Bros</h3>
</div><div tagname="Stickman Destruction" id="gameDiv" onclick="location.href='/stickman-destruction.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/233/responsive/512-2-xs.jpg" alt="FreezeNova Stickman Destruction" title="FreezeNova Stickman Destruction" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Stickman Destruction</h3>
</div><div tagname="Paper IO" id="gameDiv" onclick="location.href='/paper-io.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/436/responsive/paper-io-unblocked-xs.jpg" alt="FreezeNova Paper IO" title="FreezeNova Paper IO" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Paper IO</h3>
</div><div tagname="Gigga io" id="gameDiv" onclick="location.href='/gigga-io.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/528/responsive/gigga-io-xs.webp" alt="FreezeNova Gigga io" title="FreezeNova Gigga io" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Gigga io</h3>
</div><div tagname="StackBall.io" id="gameDiv" onclick="location.href='/stackballio.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/51/responsive/stack-xs.jpg" alt="FreezeNova StackBall.io" title="FreezeNova StackBall.io" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">StackBall.io</h3>
</div><div tagname="Madalin Stunt Cars Pro" id="gameDiv" onclick="location.href='/madalin-stunt-cars-pro.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/349/responsive/512-xs.jpg" alt="FreezeNova Madalin Stunt Cars Pro" title="FreezeNova Madalin Stunt Cars Pro" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Madalin Stunt Cars Pro</h3>
</div><div tagname="Snow War io" id="gameDiv" onclick="location.href='/snow-war-io.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/67/responsive/snow-xs.jpg" alt="FreezeNova Snow War io" title="FreezeNova Snow War io" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Snow War io</h3>
</div><div tagname="Crazy Shooters 2" id="gameDiv" onclick="location.href='/crazy-shooters-2.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/90/responsive/512-4-xs.jpg" alt="FreezeNova Crazy Shooters 2" title="FreezeNova Crazy Shooters 2" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Crazy Shooters 2</h3>
</div><div tagname="Crazy Karts" id="gameDiv" onclick="location.href='/crazy-karts.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/535/responsive/crazy-karts-game-xs.webp" alt="FreezeNova Crazy Karts" title="FreezeNova Crazy Karts" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Crazy Karts</h3>
</div><div tagname="Highway Racer 2" id="gameDiv" onclick="location.href='/highway-racer-2.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/323/responsive/512-xs.jpg" alt="FreezeNova Highway Racer 2" title="FreezeNova Highway Racer 2" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Highway Racer 2</h3>
</div><div tagname="Guerrillas.io" id="gameDiv" onclick="location.href='/guerrillas-io.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/364/responsive/guerrillas-io-xs.jpg" alt="FreezeNova Guerrillas.io" title="FreezeNova Guerrillas.io" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Guerrillas.io</h3>
</div><div tagname="Slither Snakes" id="gameDiv" onclick="location.href='/slither-snakes.html'" class="all">
    <div class="imageCon">
        <img data-src="" src="/media/posts/83/responsive/Nova-Snakes-io-512x512-xs.jpeg" alt="FreezeNova Slither Snakes" title="FreezeNova Slither Snakes" class="" loading="lazy">
    </div>
    <h3 class="innerGameDiv">Slither Snakes</h3>
</div></div></div><br>
   
   
   
                  <nav class="filter tag_list">
                        <a href="./index.html" class="filter__item">All<img src="./assets/img/games.jpg" alt="All Unblocked Games"  loading="lazy"></a>
							<a href="./2-player/index.html" class="filter__item " >2 Player<img src="./media/tags/16/2-player-2.jpg" alt="2 Player Games Unblocked"  loading="lazy"></a>
							<a href="./2d/index.html" class="filter__item " >2D<img src="./media/tags/21/2d-2.jpg" alt="2D Games Unblocked"  loading="lazy"></a>
							<a href="./3d/index.html" class="filter__item " >3D<img src="./media/tags/20/3d-2.jpg" alt="3D Games Unblocked"  loading="lazy"></a>
							<a href="./action/index.html" class="filter__item " >Action<img src="./media/tags/1/action-2.jpg" alt="Action Games Unblocked"  loading="lazy"></a>
							<a href="./adventure/index.html" class="filter__item " >Adventure<img src="./media/tags/6/adventure-2.jpg" alt="Adventure Games Unblocked"  loading="lazy"></a>
							<a href="./airplane/index.html" class="filter__item " >Airplane<img src="./media/tags/35/airplane-games.jpg" alt="Airplane Games Unblocked"  loading="lazy"></a>
							<a href="./arcade/index.html" class="filter__item " >Arcade<img src="./media/tags/7/arcade-2.jpg" alt="Arcade Games Unblocked"  loading="lazy"></a>
							<a href="./army/index.html" class="filter__item " >Army<img src="./media/tags/42/army-games.jpg" alt="Army Games Unblocked"  loading="lazy"></a>
							<a href="./basketball/index.html" class="filter__item " >Basketball<img src="./media/tags/47/basketball-games.jpg" alt="Basketball Games Unblocked"  loading="lazy"></a>
							<a href="./battle-royale/index.html" class="filter__item " >Battle Royale<img src="./media/tags/36/battle-royale-tag.jpg" alt="Battle Royale Games Unblocked"  loading="lazy"></a>
							<a href="./bike/index.html" class="filter__item " >Bike<img src="./media/tags/32/bike-games-tag.jpg" alt="Bike Games Unblocked"  loading="lazy"></a>
							<a href="./car/index.html" class="filter__item " >Car<img src="./media/tags/11/car-2.jpg" alt="Car Games Unblocked"  loading="lazy"></a>
							<a href="./clicker/index.html" class="filter__item " >Clicker<img src="./media/tags/51/clicker-games-128.jpg" alt="Clicker Games Unblocked"  loading="lazy"></a>
							<a href="./crazy/index.html" class="filter__item " >Crazy<img src="./media/tags/15/crazy-2.jpg" alt="Crazy Games Unblocked"  loading="lazy"></a>
							<a href="./dragon/index.html" class="filter__item " >Dragon<img src="./media/tags/34/dragon-games-tag.jpg" alt="Dragon Games Unblocked"  loading="lazy"></a>
							<a href="./drift/index.html" class="filter__item " >Drift<img src="./media/tags/14/drift-2.jpg" alt="Drift Games Unblocked"  loading="lazy"></a>
							<a href="./driving/index.html" class="filter__item " >Driving<img src="./media/tags/2/driving-2.jpg" alt="Driving Games Unblocked"  loading="lazy"></a>
							<a href="./escape/index.html" class="filter__item " >Escape<img src="./media/tags/46/escape-games.jpg" alt="Escape Games Unblocked"  loading="lazy"></a>
							<a href="./flash/index.html" class="filter__item " >Flash<img src="./media/tags/57/Flash-Games-Unblocked.jpg" alt="Flash Games Unblocked"  loading="lazy"></a>
							<a href="./fps/index.html" class="filter__item " >FPS<img src="./media/tags/31/fps-games-128.jpg" alt="FPS Games Unblocked"  loading="lazy"></a>
							<a href="./girl/index.html" class="filter__item " >Girl<img src="./media/tags/45/girl-games.jpg" alt="Girl Games Unblocked"  loading="lazy"></a>
							<a href="./gun/index.html" class="filter__item " >Gun<img src="./media/tags/48/gun-games.jpg" alt="Gun Games Unblocked"  loading="lazy"></a>
							<a href="./html5/index.html" class="filter__item " >HTML5<img src="./media/tags/54/HTML5-Games.-Unblocked.jpg" alt="HTML5 Games Unblocked"  loading="lazy"></a>
							<a href="./idle/index.html" class="filter__item " >Idle<img src="./media/tags/50/idle-games-unblocked.jpg" alt="Idle Games Unblocked"  loading="lazy"></a>
							<a href="./io-games/index.html" class="filter__item " >io Games<img src="./media/tags/5/iogames-2.jpg" alt="io Games Games Unblocked"  loading="lazy"></a>
							<a href="./kids/index.html" class="filter__item " >Kids<img src="./media/tags/12/kids.jpg" alt="Kids Games Unblocked"  loading="lazy"></a>
							<a href="./minecraft/index.html" class="filter__item " >Minecraft<img src="./media/tags/25/minecraft-2.jpg" alt="Minecraft Games Unblocked"  loading="lazy"></a>
							<a href="./mini/index.html" class="filter__item " >Mini<img src="./media/tags/53/mini-games-128.jpg" alt="Mini Games Unblocked"  loading="lazy"></a>
							<a href="./mobile/index.html" class="filter__item " >Mobile<img src="./media/tags/23/mobile-2.jpg" alt="Mobile Games Unblocked"  loading="lazy"></a>
							<a href="./multiplayer/index.html" class="filter__item " >Multiplayer<img src="./media/tags/3/multiplayer-2.jpg" alt="Multiplayer Games Unblocked"  loading="lazy"></a>
							<a href="./parking/index.html" class="filter__item " >Parking<img src="./media/tags/33/parking-games-tag.jpg" alt="Parking Games Unblocked"  loading="lazy"></a>
							<a href="./pixel/index.html" class="filter__item " >Pixel<img src="./media/tags/18/pixel-2.jpg" alt="Pixel Games Unblocked"  loading="lazy"></a>
							<a href="./premium/index.html" class="filter__item " >Premium<img src="./media/tags/40/premium-games.jpg" alt="Premium Games Unblocked"  loading="lazy"></a>
							<a href="./puzzle/index.html" class="filter__item " >Puzzle<img src="./media/tags/24/puzzle-2.jpg" alt="Puzzle Games Unblocked"  loading="lazy"></a>
							<a href="./racing/index.html" class="filter__item " >Racing<img src="./media/tags/13/racing-2.jpg" alt="Racing Games Unblocked"  loading="lazy"></a>
							<a href="./rally/index.html" class="filter__item " >Rally<img src="./media/tags/56/Rally-Games-Unblocked.jpg" alt="Rally Games Unblocked"  loading="lazy"></a>
							<a href="./scary/index.html" class="filter__item " >Scary<img src="./media/tags/37/scary-games.jpg" alt="Scary Games Unblocked"  loading="lazy"></a>
							<a href="./shooting/index.html" class="filter__item " >Shooting<img src="./media/tags/4/shooting-2.jpg" alt="Shooting Games Unblocked"  loading="lazy"></a>
							<a href="./simulator/index.html" class="filter__item " >Simulator<img src="./media/tags/19/simulator-2.jpg" alt="Simulator Games Unblocked"  loading="lazy"></a>
							<a href="./skill/index.html" class="filter__item " >Skill<img src="./media/tags/55/Skill-Games-Unblocked.jpg" alt="Skill Games Unblocked"  loading="lazy"></a>
							<a href="./snake/index.html" class="filter__item " >Snake<img src="./media/tags/49/snake-games.jpg" alt="Snake Games Unblocked"  loading="lazy"></a>
							<a href="./sniper/index.html" class="filter__item " >Sniper<img src="./media/tags/17/sniper-2.jpg" alt="Sniper Games Unblocked"  loading="lazy"></a>
							<a href="./sports/index.html" class="filter__item " >Sports<img src="./media/tags/38/sports-games.jpg" alt="Sports Games Unblocked"  loading="lazy"></a>
							<a href="./stickman/index.html" class="filter__item " >Stickman<img src="./media/tags/52/stickman-sm-128.jpg" alt="Stickman Games Unblocked"  loading="lazy"></a>
							<a href="./strategy/index.html" class="filter__item " >Strategy<img src="./media/tags/22/strategy-2.jpg" alt="Strategy Games Unblocked"  loading="lazy"></a>
							<a href="./tank/index.html" class="filter__item " >Tank<img src="./media/tags/39/tank-games.jpg" alt="Tank Games Unblocked"  loading="lazy"></a>
							<a href="./truck/index.html" class="filter__item " >Truck<img src="./media/tags/43/truck-games.jpg" alt="Truck Games Unblocked"  loading="lazy"></a>
							<a href="./unblocked/index.html" class="filter__item " >Unblocked<img src="./media/tags/9/unblock-128.webp" alt="Unblocked Games Unblocked"  loading="lazy"></a>
							<a href="./unity/index.html" class="filter__item " >Unity<img src="./media/tags/44/unity-games.jpg" alt="Unity Games Unblocked"  loading="lazy"></a>
							<a href="./zombie/index.html" class="filter__item " >Zombie<img src="./media/tags/41/zombie-games.jpg" alt="Zombie Games Unblocked"  loading="lazy"></a>
                  </nav>
			
			

<!--
<div class="hero">
    <div class="wrapper">
        <center><br>
<h1 style="font-size: 2.4em;">Unblocked Games FreezeNova</h1>
<p>Unblocked Games FreezeNova is a website full of unique, high quality free unlocked games to play from anywhere on Earth - no matter your location or restrictions. You can play the games at school, at home, or even at the office.</p>
</center>
    </div>
</div>
-->
			
<nav class="filter tag_list">

	<div class="wrapper">
        <center><br>
<h1 style="font-size: 2.4em;">Unblocked Games FreezeNova</h1>
<p>Unblocked Games FreezeNova is a website full of unique, high quality free unlocked games to play from anywhere on Earth - no matter your location or restrictions. You can play the games at school, at home, or even at the office.</p>
</center>
    </div>
	<br>

<img class="center-image" src="/media/files/main/Unblocked-Games-Banner.webp" alt="Unblocked Games Banner" "style= width:1200px; max-width: 100%; height: auto; align=center;">
<h2>Unblocked Games at School</h2>
<p>Looking for some fun and cool games to play during long school hours or meetings? Unblocked Games FreezeNova is a website for free online games accessible on protected networks.</p>
<p>We design our games for players of all ages and skill levels. Whether you&apos;re an avid gamer or casually hanging out, we have great titles with a wide range of tags. These tags include 2 Player, Action, Adventure, Drift, Driving, io Games, Minecraft, Mobile, Multiplayer, Shooting, Strategy and many more.</p>
<h2>No Downloads or Installations</h2>
<p>If you cannot download a game to your school Chromebook or office laptop, we&apos;ve got your back. No need for any downloads or installations on FreezeNova. You can find an array of games ranging from quick mini-plays to premium in-depth gaming experiences on this unblocked games website. Just pick a game you like and wait for it to load.&nbsp;</p>
<p>Games have straightforward controls and levels ranging from easy to difficult modes. You can achieve the best scores and win prizes. We release new games and updates regularly.&nbsp;</p>
<p>The updates offer new challenges with better graphics and colors, making the gaming experience more enjoyable. So keep coming back and check if your favorite game has received an update.</p>
<h2>Community Features</h2>
<p>We are glad to see that the FreezeNova community is growing rapidly. More and more users joining us every day. We provide a platform where gamers can engage with each other.</p>
<p>In the comment sections, share your thoughts or seek advice from other gamers. Or, compare your achievements and high scores with fellows. Here&apos;s a little secret: you may find some tips and cheats shared by developers in the comments. 😉</p>
               <h2>Meet Our Mascot: FreezeNova</h2>
<div class="game-box"style="gap: 10px; padding: 5px 0px;" >
                              <img class="game-box img" src="/media/files/main/freezenova-mascot-512.png" alt="FreezeNova the mascot" style="height: 250px; max-width: 100%;">
            <div class="game-box-text" style="max-width: 100%;">
<p>Meet the FreezeNova, the eponym of our platform and a special character who personifies the spirit of adventure. He was born in a distant galaxy where various novas illuminate the cosmos. And he came all the way to planet Earth on a mission. His duty? To guide gamers through the vast universe of unblocked online gaming.</p>
<p>Among all the novas in the sky, FreezeNova stands out with his superpowers: Everything he touches freezes, transforming into crystal-clear ice. However, this ability sometimes gets in his way, as he can be pretty clumsy. That&apos;s why we never let FreezeNova cook unless we&apos;re craving ice cream! We learned that the hard way.</p>
                </div>
        </div>
<p>Beyond his superpowers, this mate is an expert in play. He is the ultimate winner of games of any genre, whether it&apos;s a board game or an FPS.</p>
<p>Occasionally, you might catch him sharing some insider tips on our platform. It&apos;s wise to follow his gaming advice, although you might also see him bragging about his skills. Just nod and keep going when he does so; otherwise, get ready for a session, as he&apos;ll try every way to convince you! He&apos;s very persistent!</p>
<p>To sum up, he is quite a character representing endless fun and amazing gaming experiences. Join us in exciting adventures led by our luminous friend, FreezeNova. He has a lot more to reveal as you dive into the waters of unblocked games!</p>
 

<h2>Discover Popular Tags</h2>
<p>Our unblocked games extend to a wide range of genres. You can filter games by browsing dedicated tag pages such as arcade, action, driving and many more. Moreover, you have the option to choose between 2D, 3D, or Premium games based on graphics.</p>
<p>If you&apos;re looking for a game to enjoy with friends, you can discover 2-player, multiplayer or io games tags as well. Feel free to explore all and find the one that is just your cup of coffee. Need further help deciding? Here are the most popular tags on Unblocked Games FreezeNova:</p>
<ul>
    <li><a href="/car/index.html">Car Games</a></li>
    <li><a href="/shooting/index.html">Shooting Games</a></li>
    <li><a href="/io-games/index.html">io Games Unblocked</a></li>
    <li><a href="/2-player/index.html">2 Player Games</a></li>
</ul>
<h2>The Best Unblocked Games</h2>
<img class="center-image" src="/media/files/main/Best-Unblocked-Games-List.webp" alt="Best Unblocked Games" "style= max-width: 100%; height: auto; align=center;">
<p>We have picked the <strong>best games that are not blocked on school computers</strong>. Ranging from driving to shooting games unblocked, we have at least one game on this list that will appeal to you.</p>

<h3>Drift Hunters 2024</h3>
<p>In this latest version of Drift Hunters, you can break records on maps like New Zealand, Nevada, and Ohio. Your aim is to achieve the highest drifting scores with your favorite car. Drift Hunters 2024 has new maps, vehicles, and lots of tuning options to fully customize your car. Better graphics and ultra-realistic car driving performance are the other upsides of the updated version.</p>
<p>Playing is not hard, but mastering is. Choose your arena and drive your car on diverse maps like racetracks, playgrounds, and drifting roads. Make the highest drifting scores. Earn money based on your score.&nbsp;</p>
<p>Collect your money to upgrade parts or buy new cars in a garage where 26 famous drifting cars are available. Start with a car similar to the iconic Toyota AE86, and unlock more as you progress.</p>
<p>We understand that master drifters prefer manual. So, while upgrading this game, we have included a switch from an automatic to a manual gearbox. Enjoy&nbsp;<a href="/drift-hunters-2024.html">Drift Hunters 2024</a>&nbsp;game with awesome graphics and easy controls for flipping, spinning, and drifting.</p>
<h3>Highway Traffic</h3>
<p>Most individuals don&apos;t love traffic in the real world. But in the gaming world, it&apos;s one of the most loved things. You&apos;ll change your opinion about traffic when you play the&nbsp;<a href="/highway-traffic.html">Highway Traffic</a>&nbsp;game. The entire game revolves around avoiding accidents while driving down the highway and dodging other road users.</p>
<p>It can be fun and difficult when other cars suddenly stop, slow down, and speed up. So, you must always be cautious and prepared to make fast moves. This game is not about racing. It is about being patient and navigating through traffic on the highway.</p>
<p>You&apos;ll collect as many points as possible if you travel a long distance without hitting other vehicles. To reach higher levels, you must know that steering through busy roads can be challenging. So, improve your abilities and gain more knowledge.</p>
<p>The Highway Traffic game features different modes, making it more fun. You have different car styles, models. Weather options enhance the challenge. On top of that, you are just a few clicks away from playing the Highway Traffic game.</p>
<h3>Real Flight Simulator</h3>
<p>Unblocked Games Freezenova provides the&nbsp;<a href="/real-flight-simulator.html">Real Flight Simulator</a>&nbsp;game, allowing you to experience the entire pilot&apos;s life. The game gives an actual flying experience with various planes, day-night cycles, and realistic weather conditions.</p>
<p>With this simulator game, you&apos;re in charge of the aircraft and the heights you want to achieve. To fly successfully, you need to review the control information in the top left corner of your device&apos;s screen.</p>
<h3>Masked Special Forces</h3>
<p>Satisfy your need for FPS action by playing the&nbsp;<a href="/masked-special-forces.html">Masked Special Forces</a>. This game will keep you entertained for several hours. Fantastic weapons and maps make it even more fun.</p>
<p>Pick your lead-out before the battle. Compete against other players worldwide. Use the code to load and save your game data.</p>
<h3>Tap Tap Shots</h3>
<p>Tap Tap Shots is a fast-paced basketball game where you need to make as many baskets as possible within a limited time. Adjust your shot angle and land the ball in the basket.</p>
<p>Controls are easy peasy. It&apos;s only one button. Click (or tap) to jump the ball. Watch the timer to make a precise shot before time runs out.</p>
<p>A regular shot will bring you 1 point, while a perfect shot comes with 2 points. You can make a streak to double up your score. Overall,&nbsp;<a href="/tap-tap-shots.html">Tap Tap Shots</a>&nbsp;definitely deserves a chance from skill game lovers who love to play browser games on mobiles or tablets.</p>
<h3>Basketball Stars</h3>
<p>Another fantastic sports game is&nbsp;<a href="/basketball-stars.html">Basketball Stars</a>. You can choose your basketball club and join tournaments. You can play this unblocked game solo or with a friend. It features NBA players like LeBron James and James Harden.</p>
<p>In 1 Player mode, you can play tournaments, practice and adjust the difficulty level. In 2 Player mode, you can play against a friend, team up, or play against the computer.</p>
<p>Choose famous basketball stars and use special powers to score. Get ready for hat tricks.</p>
<h3>Love Tester</h3>
<p>This one is rather a fortune-telling machine than a game.&nbsp;<a href="/love-tester.html">Love Tester</a>&nbsp;adds a modern twist to the classic flower petal game.</p>
<p>Simply enter your name and your crush&apos;s name to discover your chances. It&apos;s a fun way to test your romantic love. Give it a try and see what the love meter says!</p>
<h2>Before You Go</h2>
<p>We are always looking for ways to improve our platform and provide the best experience for our users. So, we value your feedback when expanding our games library. We hope you enjoy your time on Unblocked Games FreezeNova and look forward to hearing from you soon!</p>
<p>Whether you&apos;re a student or a worker, FreezeNova offers exciting online games unblocked. The platform offers unblocked access and a user-friendly interface.</p>
<p>Best of all is a large library of amazing games. An enjoyable and seamless gaming experience awaits you here! Have fun!</p>
    
</nav>


<script src="/assets/scripts/index.js"></script>

</main>
<footer class="footer">
   <div class="wrapper">
      <div class="footer__top">
         <a class="logo footer__logo" href="./index.html">
                <img src="./media/website/unblocked-games-freezenova-logo.webp" alt="Unblocked Games FreezeNova" width="726" height="90">
         </a>
            <div class="footer__nav-3">
               <h3 class="h6">Menu</h3>
               <ul class="footer__nav">
                     <li class="active">
                           <a href="./index.html"  target="_self">
                              Home
                           </a>
                     </li>
                     <li>
                           <a href="./new-games.html"  target="_self">
                              New
                           </a>
                     </li>
                     <li>
                           <a href="./action/index.html"  target="_self">
                              Action
                           </a>
                     </li>
                     <li>
                           <a href="./car/index.html"  target="_self">
                              Car
                           </a>
                     </li>
                     <li>
                           <a href="./driving/index.html"  target="_self">
                              Driving
                           </a>
                     </li>
                     <li>
                           <a href="./multiplayer/index.html"  target="_self">
                              Multiplayer
                           </a>
                     </li>
                     <li>
                           <a href="./shooting/index.html"  target="_self">
                              Shooting
                           </a>
                     </li>
                     <li>
                           <a href="./io-games/index.html"  target="_self">
                              .io Games
                           </a>
                     </li>
                     <li>
                           <a href="./privacy-policy.html"  target="_self">
                              Privacy Policy
                           </a>
                     </li>
                     <li>
                           <a href="./chat.html"  target="_self">
                              Chat
                           </a>
                     </li>
                     <li>
                           <a href="./about.html"  target="_self">
                              About
                           </a>
                     </li>
                     <li>
                           <a href="./game-developers.html"  target="_self">
                              Game Developers
                           </a>
                     </li>
                     <li>
                           <a href="https://github.com/freezenova/freezenova.github.io"  target="_self">
                              Self-hosting
                           </a>
                     </li>
                     <li>
                           <a href="./contact.html"  target="_self">
                              Contact
                           </a>
                     </li>
               </ul>
            </div>
      </div>
      <div class="footer__bottom">
            <div class="footer__copyright">
               Are you looking for a place to play your favorite unblocked games? <br>
Look no further than FreezeNova. <br>
We offer a community of gamers who are always looking for new challengers. <br>
With our easy-to-use browser-based platform, you can start playing right away. <br>
So come and join the fun today!<br>
We developed this website so you can play your favorite games from anywhere. <br>
Email us at contact@freezenova.com
<br>
Developed by FreezeNova
<br>
            </div>
      </div>
   </div>
      <button onclick="backToTopFunction()" id="backToTop" class="footer__bttop" aria-label="Back to top" title="Back to top">
         <svg>
            <use xlink:href="./assets/svg/svg-map.svg#toparrow"/>
         </svg>
      </button>
</footer>
   <script defer src="./assets/js/infinite-scroll.pkgd.min.js?v=014df05a95a4e2d99b39516b72cfea1f"></script>
         <script defer src="./assets/js/isotope.pkgd.min.js?v=2afcff647ed260006faa71c8e779e8d4"></script>
         <script>
            window.addEventListener("DOMContentLoaded", function () {
               // init Isotope
               var iso = new Isotope('.l-isotope', {
                  itemSelector: '.c-card',
                  layoutMode: 'fitRows',
                  masonry: {
                     columnWidth: '.c-card'
                  },
                  percentPosition: true,
                  transitionDuration: "0.6s"
               });


               //Skip over Infinite Scroll's outlayer behavior, needed to avaoid laodign the original src atribbute image
               InfiniteScroll.prototype.appendOutlayerItems = function( fragment, appendReady ) {
                  appendReady();
               };
               if ( document.querySelector('.pagination__next') ) {
                  var infScroll = document.querySelector('.js-infinitescroll');
                  var infScroll = new InfiniteScroll(infScroll, {
                     path    : '.pagination__next',
                     append  : '.c-card',
                     checkLastPage: true,
                     outlayer: iso,
                     hideNav: '.pagination',
                        button: '.view-more',
                        scrollThreshold: false,
                     history :  false 
                  });

                  infScroll.on('append', function () {
                     publiiDetectLoadedImages();
                  });
               }
               // bind filter button click
               var filtersElem = document.querySelector('.filter');
               if (filtersElem) {
                  filtersElem.addEventListener('click', function (event) {
                     if (!matchesSelector(event.target, 'button')) {
                        return;
                     }
                     var filterValue = event.target.getAttribute('data-filter');
                     filterValue = filterValue;
                     iso.arrange({
                        filter: filterValue
                     });
                  });
                  // change is-checked class on buttons
                  var buttonGroups = document.querySelectorAll('.filter');
                  for (var i = 0, len = buttonGroups.length; i < len; i++) {
                     var buttonGroup = buttonGroups[i];
                     radioButtonGroup(buttonGroup);
                  }
                  function radioButtonGroup(buttonGroup) {
                     buttonGroup.addEventListener('click', function (event) {
                        if (!matchesSelector(event.target, 'button')) {
                           return;
                        }
                        buttonGroup.querySelector('.is-active').classList.remove('is-active');
                        event.target.classList.add('is-active');
                     });
                  }            
               }
               var filtersElem = document.querySelector('.filter.tag_list');
               if (filtersElem) {
                  filtersElem.addEventListener('click', function (event) {
                     if (!matchesSelector(event.target, 'button')) {
                        return;
                     }
                     var filterValue = event.target.getAttribute('data-filter');
                     filterValue = filterValue;
                     iso.arrange({
                        filter: filterValue
                     });
                  });
                  // change is-checked class on buttons
                  var buttonGroups = document.querySelectorAll('.filter.tag_list');
                  for (var i = 0, len = buttonGroups.length; i < len; i++) {
                     var buttonGroup = buttonGroups[i];
                     radioButtonGroup(buttonGroup);
                  }
                  function radioButtonGroup(buttonGroup) {
                     buttonGroup.addEventListener('click', function (event) {
                        if (!matchesSelector(event.target, 'button')) {
                           return;
                        }
                        buttonGroup.querySelector('.is-active').classList.remove('is-active');
                        event.target.classList.add('is-active');
                     });
                  }            
               }
            });
         </script>
<script> window.publiiThemeMenuConfig = { mobileMenuMode: 'sidebar', animationSpeed: 300, submenuWidth: 'auto', doubleClickTime: 500, mobileMenuExpandableSubmenus: true, relatedContainerForOverlayMenuSelector: '.navbar', }; </script>
<script defer src="./assets/js/scripts.min.js?v=f38d0d176b831ac1c3053faa12bb916d"></script>
   <script>  
      function publiiDetectLoadedImages () {
         var images = document.querySelectorAll('img[loading]:not(.is-loaded)');
         for (var i = 0; i < images.length; i++) {
            if (images[i].complete) {
                  images[i].classList.add('is-loaded');
                  images[i].parentNode.classList.add('is-loaded');
            } else {
                  images[i].addEventListener('load', function () {
                     this.classList.add('is-loaded');
                     this.parentNode.classList.add('is-loaded');
                  }, false);
            }
         }
      }
      publiiDetectLoadedImages();
   </script>






			<script>
				window.publiiStaticSearchConfig = { 
					baseURL: '.',
					minCharCount: 3,
					maxResultsCount: 20,
					showPopupOnInputClick: false,
					customTriggerSelector: '',
					engineSettings: {
						tokenize: 'forward',
						charset: 'latin:extra',
						language: 'en-GB',
						cache: false,
						suggest: false
					},
					indexSettings: {
						resultsDescription: 'off',
						indexPostTitles: true,
						indexPostExcerpts: false,
						indexPostHeadings: false,
						indexPostAuthors: false,
						indexPostMetaDescription: false,
						indexTagNames: true,
						indexTagDescription: false,
						indexTagMetaDescription: false
					},
					translations: {
						inputPlaceholder: 'Search...',
						searchEmptyState: 'Type to start a search',
						tooShortPhraseState: 'Enter at least 3 characters to search...',
						noResults: 'No results found!',
						buttonClose: 'Close'
					}
				};
			</script>
			<script src="./media/plugins/staticSearch/flexsearch.bundle.js"></script>
			<script src="./media/plugins/staticSearch/static.search.min.js"></script>
    	
<script>
   var liElements = document.querySelectorAll('ul > li');

   liElements.forEach(function(liElement) {
   var aElement = liElement.querySelector('a');
   liElement.addEventListener('click', function() {
      aElement.click();
   });
});
</script>
<script>
   document.addEventListener("DOMContentLoaded", function () {
      const toggleButton = document.querySelector(".toggle_button");
      const closeButton = document.querySelector(".close");
      const sidebar = document.querySelector(".sidebar");
      const main = document.querySelector(".main");

      toggleButton.addEventListener("click", function () {
        sidebar.classList.toggle("collapse");
        toggleButton.classList.toggle("rotate");
        main.classList.toggle("content");
      });

      closeButton.addEventListener("click", function () {
        sidebar.classList.remove("collapse");
      });
   });       
</script>
<script>
   /*const custom_searchButton = document.querySelector(".js-search-btn");
   const custom_searchOverlay = document.querySelector(".js-search-overlay");

   function setStateInLocalStorage(state) {
      localStorage.setItem("customSearchOverlayState", state);
   }

   function getStateFromLocalStorage() {
      return localStorage.getItem("customSearchOverlayState");
   }

   if (getStateFromLocalStorage() === null) {
      setStateInLocalStorage("expanded1");
   }

   const initialState = getStateFromLocalStorage();
   if (initialState === "expanded1") {
      custom_searchOverlay.classList.add("expanded1");
   } else {
      custom_searchOverlay.classList.remove("expanded1");
   }

   custom_searchButton.addEventListener("click", function () {
      if (custom_searchOverlay.classList.contains("expanded1")) {
         custom_searchOverlay.classList.remove("expanded1");
         setStateInLocalStorage("collapsed");
      } else {
         custom_searchOverlay.classList.add("expanded1");
         setStateInLocalStorage("expanded1");
         }
      });

   // Original code from the theme
   var searchButton = document.querySelector(".js-search-btn");
   var searchOverlay = document.querySelector(".js-search-overlay");
   var searchInput = document.querySelector("[type='search']");

   if (searchButton) {
      searchButton.addEventListener("click", function() {
         searchOverlay.classList.toggle("expanded");
         if (searchInput) {
            setTimeout(function() {
               if (searchOverlay.classList.contains("expanded")) {
                  searchInput.focus()
               }
            }, 60)
         }
      });
      searchOverlay.addEventListener("click", function(a) {
         a.stopPropagation()
      });
      searchButton.addEventListener("click", function(a) {
         a.stopPropagation()
      });
      document.body.addEventListener("click", function() {
         searchOverlay.classList.remove("expanded")
      });
   }*/
</script>




</body>
</html>

