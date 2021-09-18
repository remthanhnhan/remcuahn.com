
<!DOCTYPE html>
<!--[if IE 9 ]> <html lang="vi" class="ie9 loading-site no-js"> <![endif]-->
<!--[if IE 8 ]> <html lang="vi" class="ie8 loading-site no-js"> <![endif]-->
<!--[if (gte IE 9)|!(IE)]><!--><html lang="vi" class="loading-site no-js"> <!--<![endif]-->
<head><script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=Zr9yTT2iR_hShbGrQYy4ZXAd0qwdVhKadkZ7AZn4rrilXhdOHYdaCvcRqe4UbmPT" charset="UTF-8"></script><link rel="stylesheet" crossorigin="anonymous" href="https://gc.kis.v2.scr.kaspersky-labs.com/E3E8934C-235A-4B0E-825A-35A08381A191/abn/main.css?attr=aHR0cHM6Ly9yZW1jdWFobi5jb20v"/><script>if(navigator.userAgent.match(/MSIE|Internet Explorer/i)||navigator.userAgent.match(/Trident\/7\..*?rv:11/i)){var href=document.location.href;if(!href.match(/[?&]nowprocket/)){if(href.indexOf("?")==-1){if(href.indexOf("#")==-1){document.location.href=href+"?nowprocket=1"}else{document.location.href=href.replace("#","?nowprocket=1#")}}else{if(href.indexOf("#")==-1){document.location.href=href+"&nowprocket=1"}else{document.location.href=href.replace("#","&nowprocket=1#")}}}}</script><script>class RocketLazyLoadScripts{constructor(e){this.triggerEvents=e,this.eventOptions={passive:!0},this.userEventListener=this.triggerListener.bind(this),this.delayedScripts={normal:[],async:[],defer:[]},this.allJQueries=[]}_addUserInteractionListener(e){this.triggerEvents.forEach((t=>window.addEventListener(t,e.userEventListener,e.eventOptions)))}_removeUserInteractionListener(e){this.triggerEvents.forEach((t=>window.removeEventListener(t,e.userEventListener,e.eventOptions)))}triggerListener(){this._removeUserInteractionListener(this),this._loadEverythingNow()}async _loadEverythingNow(){this._handleDocumentWrite(),this._registerAllDelayedScripts(),this._preloadAllScripts(),await this._loadScriptsFromList(this.delayedScripts.normal),await this._loadScriptsFromList(this.delayedScripts.defer),await this._loadScriptsFromList(this.delayedScripts.async),await this._triggerDOMContentLoaded(),await this._triggerWindowLoad(),window.dispatchEvent(new Event("rocket-allScriptsLoaded"))}_registerAllDelayedScripts(){document.querySelectorAll("script[type=rocketlazyloadscript]").forEach((e=>{e.hasAttribute("src")?e.hasAttribute("async")&&!1!==e.async?this.delayedScripts.async.push(e):e.hasAttribute("defer")&&!1!==e.defer||"module"===e.getAttribute("data-rocket-type")?this.delayedScripts.defer.push(e):this.delayedScripts.normal.push(e):this.delayedScripts.normal.push(e)}))}async _transformScript(e){return await this._requestAnimFrame(),new Promise((t=>{var n=document.createElement("script");[...e.attributes].forEach((e=>{let t=e.nodeName;"type"!==t&&("data-rocket-type"===t&&(t="type"),n.setAttribute(t,e.nodeValue))})),e.hasAttribute("src")?(n.addEventListener("load",t),n.addEventListener("error",t)):(n.text=e.text,t()),e.parentNode.replaceChild(n,e)}))}async _loadScriptsFromList(e){const t=e.shift();return t?(await this._transformScript(t),this._loadScriptsFromList(e)):Promise.resolve()}_preloadAllScripts(){var e=document.createDocumentFragment();[...this.delayedScripts.normal,...this.delayedScripts.defer,...this.delayedScripts.async].forEach((t=>{const n=t.getAttribute("src");if(n){const t=document.createElement("link");t.href=n,t.rel="preload",t.as="script",e.appendChild(t)}})),document.head.appendChild(e)}_delayEventListeners(){let e={};function t(t,n){!function(t){function n(n){return e[t].eventsToRewrite.indexOf(n)>=0?"rocket-"+n:n}e[t]||(e[t]={originalFunctions:{add:t.addEventListener,remove:t.removeEventListener},eventsToRewrite:[]},t.addEventListener=function(){arguments[0]=n(arguments[0]),e[t].originalFunctions.add.apply(t,arguments)},t.removeEventListener=function(){arguments[0]=n(arguments[0]),e[t].originalFunctions.remove.apply(t,arguments)})}(t),e[t].eventsToRewrite.push(n)}function n(e,t){const n=e[t];Object.defineProperty(e,t,{get:n||function(){},set:n=>{e["rocket"+t]=n}})}t(document,"DOMContentLoaded"),t(window,"DOMContentLoaded"),t(window,"load"),t(window,"pageshow"),t(document,"readystatechange"),n(document,"onreadystatechange"),n(window,"onload"),n(window,"onpageshow")}_delayJQueryReady(e){let t;Object.defineProperty(window,"jQuery",{get:()=>t,set(n){if(n&&n.fn&&!e.allJQueries.includes(n)){n.fn.ready=n.fn.init.prototype.ready=function(t){e.domReadyFired?t.bind(document)(n):document.addEventListener("rocket-DOMContentLoaded",(()=>t.bind(document)(n)))};const t=n.fn.on;n.fn.on=n.fn.init.prototype.on=function(){if(this[0]===window){function e(e){return e.split(" ").map((e=>"load"===e?"rocket-load":e)).join(" ")}"string"==typeof arguments[0]||arguments[0]instanceof String?arguments[0]=e(arguments[0]):"object"==typeof arguments[0]&&Object.keys(arguments[0]).forEach((t=>{delete Object.assign(arguments[0],{[e(t)]:arguments[0][t]})[t]}))}return t.apply(this,arguments),this},e.allJQueries.push(n)}t=n}})}async _triggerDOMContentLoaded(){this.domReadyFired=!0,await this._requestAnimFrame(),document.dispatchEvent(new Event("rocket-DOMContentLoaded")),await this._requestAnimFrame(),window.dispatchEvent(new Event("rocket-DOMContentLoaded")),await this._requestAnimFrame(),document.dispatchEvent(new Event("rocket-readystatechange")),await this._requestAnimFrame(),document.rocketonreadystatechange&&document.rocketonreadystatechange()}async _triggerWindowLoad(){await this._requestAnimFrame(),window.dispatchEvent(new Event("rocket-load")),await this._requestAnimFrame(),window.rocketonload&&window.rocketonload(),await this._requestAnimFrame(),this.allJQueries.forEach((e=>e(window).trigger("rocket-load"))),window.dispatchEvent(new Event("rocket-pageshow")),await this._requestAnimFrame(),window.rocketonpageshow&&window.rocketonpageshow()}_handleDocumentWrite(){const e=new Map;document.write=document.writeln=function(t){const n=document.currentScript,r=document.createRange(),i=n.parentElement;let o=e.get(n);void 0===o&&(o=n.nextSibling,e.set(n,o));const a=document.createDocumentFragment();r.setStart(a,0),a.appendChild(r.createContextualFragment(t)),i.insertBefore(a,o)}}async _requestAnimFrame(){return new Promise((e=>requestAnimationFrame(e)))}static run(){const e=new RocketLazyLoadScripts(["keydown","mouseover","touchmove","touchstart","wheel"]);e._delayEventListeners(),e._delayJQueryReady(e),e._addUserInteractionListener(e)}}RocketLazyLoadScripts.run();
</script>
	<meta charset="UTF-8" />
	<link rel="profile" href="http://gmpg.org/xfn/11" />
	<link rel="pingback" href="https://remcuahn.com/xmlrpc.php" />

	<script type="rocketlazyloadscript">(function(html){html.className = html.className.replace(/\bno-js\b/,'js')})(document.documentElement);</script>
<meta name='robots' content='index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1' />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1" />
	<!-- This site is optimized with the Yoast SEO Premium plugin v16.8 (Yoast SEO v16.8) - https://yoast.com/wordpress/plugins/seo/ -->
	<title>Rèm cửa đi, cửa sổ phòng khách, phòng ngủ đẹp, giá rẻ - remcuahn.com</title><style id="rocket-critical-css">.mbwph-fbc{display:none}.screen-reader-text{border:0;clip:rect(1px,1px,1px,1px);-webkit-clip-path:inset(50%);clip-path:inset(50%);height:1px;margin:-1px;overflow:hidden;overflow-wrap:normal!important;word-wrap:normal!important;padding:0;position:absolute!important;width:1px}@font-face{font-display:swap;font-family:eicons;src:url(https://remcuahn.com/wp-content/plugins/elementor/assets/lib/eicons/fonts/eicons.eot?5.11.0);src:url(https://remcuahn.com/wp-content/plugins/elementor/assets/lib/eicons/fonts/eicons.eot?5.11.0#iefix) format("embedded-opentype"),url(https://remcuahn.com/wp-content/plugins/elementor/assets/lib/eicons/fonts/eicons.woff2?5.11.0) format("woff2"),url(https://remcuahn.com/wp-content/plugins/elementor/assets/lib/eicons/fonts/eicons.woff?5.11.0) format("woff"),url(https://remcuahn.com/wp-content/plugins/elementor/assets/lib/eicons/fonts/eicons.ttf?5.11.0) format("truetype"),url(https://remcuahn.com/wp-content/plugins/elementor/assets/lib/eicons/fonts/eicons.svg?5.11.0#eicon) format("svg");font-weight:400;font-style:normal}[class^=eicon]{display:inline-block;font-family:eicons;font-size:inherit;font-weight:400;font-style:normal;font-variant:normal;line-height:1;text-rendering:auto;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.eicon-chevron-right:before{content:'\e87d'}.eicon-chevron-left:before{content:'\e87e'}.elementor-column-gap-narrow>.elementor-row>.elementor-column>.elementor-element-populated{padding:5px}.elementor-column-gap-default>.elementor-row>.elementor-column>.elementor-element-populated{padding:10px}@media (max-width:767px){.elementor-column{width:100%}}.elementor-screen-only,.screen-reader-text{position:absolute;top:-10000em;width:1px;height:1px;margin:-1px;padding:0;overflow:hidden;clip:rect(0,0,0,0);border:0}.elementor{-webkit-hyphens:manual;-ms-hyphens:manual;hyphens:manual}.elementor *,.elementor :after,.elementor :before{-webkit-box-sizing:border-box;box-sizing:border-box}.elementor a{-webkit-box-shadow:none;box-shadow:none;text-decoration:none}.elementor img{height:auto;max-width:100%;border:none;-webkit-border-radius:0;border-radius:0;-webkit-box-shadow:none;box-shadow:none}:root{--page-title-display:block}.elementor-section{position:relative}.elementor-section .elementor-container{display:-webkit-box;display:-ms-flexbox;display:flex;margin-right:auto;margin-left:auto;position:relative}@media (max-width:1024px){.elementor-section .elementor-container{-ms-flex-wrap:wrap;flex-wrap:wrap}}.elementor-section.elementor-section-boxed>.elementor-container{max-width:1140px}.elementor-section.elementor-section-stretched{position:relative;width:100%}.elementor-row{width:100%;display:-webkit-box;display:-ms-flexbox;display:flex}@media (max-width:1024px){.elementor-row{-ms-flex-wrap:wrap;flex-wrap:wrap}}.elementor-widget-wrap{position:relative;width:100%;-ms-flex-wrap:wrap;flex-wrap:wrap;-ms-flex-line-pack:start;align-content:flex-start}.elementor:not(.elementor-bc-flex-widget) .elementor-widget-wrap{display:-webkit-box;display:-ms-flexbox;display:flex}.elementor-widget-wrap>.elementor-element{width:100%}.elementor-widget{position:relative}.elementor-widget:not(:last-child){margin-bottom:20px}.elementor-column{min-height:1px}.elementor-column,.elementor-column-wrap{position:relative;display:-webkit-box;display:-ms-flexbox;display:flex}.elementor-column-wrap{width:100%}@media (min-width:768px){.elementor-column.elementor-col-100{width:100%}}@media (max-width:767px){.elementor-column{width:100%}}[class^=eicon]{display:inline-block;font-family:eicons;font-size:inherit;font-weight:400;font-style:normal;font-variant:normal;line-height:1;text-rendering:auto;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.eicon-chevron-right:before{content:"\e87d"}.eicon-chevron-left:before{content:"\e87e"}.elementor-button{display:inline-block;line-height:1;background-color:#818a91;font-size:15px;padding:12px 24px;-webkit-border-radius:3px;border-radius:3px;color:#fff;fill:#fff;text-align:center}.elementor-button:visited{color:#fff}.elementor-button.elementor-size-xs{font-size:13px;padding:10px 20px;-webkit-border-radius:2px;border-radius:2px}.elementor-heading-title{padding:0;margin:0;line-height:1}.elementor-widget-heading .elementor-heading-title.elementor-size-medium{font-size:19px}.swiper-container{margin-left:auto;margin-right:auto;position:relative;overflow:hidden;z-index:1}.swiper-wrapper{position:relative;width:100%;height:100%;z-index:1;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-sizing:content-box;box-sizing:content-box}.swiper-wrapper{-webkit-transform:translateZ(0);transform:translateZ(0)}.swiper-slide{-ms-flex-negative:0;flex-shrink:0;width:100%;height:100%;position:relative}.elementor-swiper{position:relative}.elementor-main-swiper{position:static}.elementor-swiper-button{position:absolute;display:-webkit-inline-box;display:-ms-inline-flexbox;display:inline-flex;z-index:1;font-size:25px;color:hsla(0,0%,93.3%,.9);top:50%;-webkit-transform:translateY(-50%);-ms-transform:translateY(-50%);transform:translateY(-50%)}.elementor-swiper-button-prev{left:10px}.elementor-swiper-button-next{right:10px}.elementor-kit-2282{--e-global-color-primary:#6EC1E4;--e-global-color-secondary:#54595F;--e-global-color-text:#7A7A7A;--e-global-color-accent:#61CE70;--e-global-typography-primary-font-family:"Roboto";--e-global-typography-primary-font-weight:600;--e-global-typography-secondary-font-family:"Roboto Slab";--e-global-typography-secondary-font-weight:400;--e-global-typography-text-font-family:"Roboto";--e-global-typography-text-font-weight:400;--e-global-typography-accent-font-family:"Roboto";--e-global-typography-accent-font-weight:500}.elementor-section.elementor-section-boxed>.elementor-container{max-width:1140px}.elementor-widget:not(:last-child){margin-bottom:20px}@media (max-width:1024px){.elementor-section.elementor-section-boxed>.elementor-container{max-width:1024px}}@media (max-width:767px){.elementor-section.elementor-section-boxed>.elementor-container{max-width:767px}}.elementor-slides .swiper-slide-bg{-webkit-background-size:cover;background-size:cover;background-position:50%;background-repeat:no-repeat;min-width:100%;min-height:100%}.elementor-slides .swiper-slide-inner{background-repeat:no-repeat;background-position:50%;position:absolute;top:0;left:0;bottom:0;right:0;padding:50px;margin:auto}.elementor-slides .swiper-slide-inner{color:#fff;display:-webkit-box;display:-ms-flexbox;display:flex}.elementor-slides .swiper-slide-inner .elementor-slide-heading{font-size:35px;font-weight:700;line-height:1}.elementor-slides .swiper-slide-inner .elementor-slide-description{font-size:17px;line-height:1.4}.elementor-slides .swiper-slide-inner .elementor-slide-description:not(:last-child),.elementor-slides .swiper-slide-inner .elementor-slide-heading:not(:last-child){margin-bottom:30px}.elementor-slides .swiper-slide-inner .elementor-slide-button{border:2px solid #fff;color:#fff;background:transparent;display:inline-block}.elementor-slides .swiper-slide-inner .elementor-slide-button{background:transparent;color:inherit;text-decoration:none}.elementor--v-position-bottom .swiper-slide-inner{-webkit-box-align:end;-ms-flex-align:end;align-items:flex-end}.elementor--h-position-right .swiper-slide-inner{-webkit-box-pack:end;-ms-flex-pack:end;justify-content:flex-end}@media (max-width:767px){.elementor-slides .swiper-slide-inner{padding:30px}.elementor-slides .swiper-slide-inner .elementor-slide-heading{font-size:23px;line-height:1;margin-bottom:15px}.elementor-slides .swiper-slide-inner .elementor-slide-description{font-size:13px;line-height:1.4;margin-bottom:15px}}.swiper-slide{border-style:solid;border-width:0;overflow:hidden}.swiper-slide a{display:inline}.elementor-widget-heading .elementor-heading-title{color:var(--e-global-color-primary);font-family:var(--e-global-typography-primary-font-family),Sans-serif;font-weight:var(--e-global-typography-primary-font-weight)}.elementor-widget-slides .elementor-slide-heading{font-family:var(--e-global-typography-primary-font-family),Sans-serif;font-weight:var(--e-global-typography-primary-font-weight)}.elementor-widget-slides .elementor-slide-description{font-family:var(--e-global-typography-secondary-font-family),Sans-serif;font-weight:var(--e-global-typography-secondary-font-weight)}.elementor-widget-slides .elementor-slide-button{font-family:var(--e-global-typography-accent-font-family),Sans-serif;font-weight:var(--e-global-typography-accent-font-weight)}.elementor-9 .elementor-element.elementor-element-917d7da>.elementor-container{max-width:1180px}.elementor-9 .elementor-element.elementor-element-917d7da{border-radius:0px 0px 0px 0px}.elementor-9 .elementor-element.elementor-element-917d7da{margin-top:0px;margin-bottom:0px;padding:0px 0px 0px 0px}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-repeater-item-36475e5 .swiper-slide-bg{background-color:#bbbbbb;background-image:url(https://remcuahn.com/wp-content/uploads/2019/08/rem-vai-mot-mau.jpg);background-size:cover}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-repeater-item-ba96e20 .swiper-slide-bg{background-color:#bbbbbb;background-image:url(https://remcuahn.com/wp-content/uploads/2019/08/rem-roman-2-lop-co-yem.jpg);background-size:cover}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-repeater-item-9d7bae2 .swiper-slide-bg{background-color:#bbbbbb;background-image:url(https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-thanh-nhan_ha-dong.jpg);background-size:cover}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-repeater-item-f31f37b .swiper-slide-bg{background-color:#bbbbbb;background-image:url(https://remcuahn.com/wp-content/uploads/2019/08/rem-go-tu-nhien-thanh-nhan.jpg);background-size:cover}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-repeater-item-1cf3e74 .swiper-slide-bg{background-color:#bbbbbb;background-image:url(https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-baner.jpg);background-size:cover}.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide{height:500px}.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide-contents{max-width:100%}.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide-inner{padding:30px 30px 30px 30px;text-align:center}.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide-inner .elementor-slide-heading:not(:last-child){margin-bottom:8px}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-slide-heading{font-family:"Roboto",Sans-serif;font-weight:500;text-transform:uppercase;line-height:1.3em;letter-spacing:1.8px}.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide-inner .elementor-slide-description:not(:last-child){margin-bottom:8px}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-slide-description{color:#ffffff;font-family:"Open Sans Condensed",Sans-serif;font-size:22px;font-weight:500;font-style:italic;letter-spacing:0.8px}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-slide-button{font-size:16px;font-weight:500;border-width:0px;border-radius:10px;background-color:#FF0000}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-swiper-button{font-size:22px}.elementor-9 .elementor-element.elementor-element-8bba405>.elementor-widget-container{margin:0px 0px 0px 0px;padding:0px 0px 0px 0px}.elementor-9 .elementor-element.elementor-element-b81c69e>.elementor-container{max-width:1180px}.elementor-9 .elementor-element.elementor-element-c4ed63f .elementor-spacer-inner{height:10px}.elementor-9 .elementor-element.elementor-element-57b4f2c{text-align:center}.elementor-9 .elementor-element.elementor-element-57b4f2c .elementor-heading-title{color:#333333;font-family:"Lato",Sans-serif;font-weight:500;text-transform:uppercase;line-height:1.8em;letter-spacing:1.5px}.elementor-9 .elementor-element.elementor-element-24c424e>.elementor-container{max-width:1150px}.elementor-9 .elementor-element.elementor-element-59b2ec3{text-align:center}.elementor-9 .elementor-element.elementor-element-59b2ec3 .elementor-heading-title{color:#333333;font-family:"Lato",Sans-serif;font-weight:500;text-transform:uppercase;line-height:1.8em;letter-spacing:1.5px}.elementor-9 .elementor-element.elementor-element-d5611b2>.elementor-container{max-width:1150px}.elementor-9 .elementor-element.elementor-element-d6d7125.elementor-wc-products .attachment-woocommerce_thumbnail{margin-bottom:0px}@media (max-width:1024px) and (min-width:768px){.elementor-9 .elementor-element.elementor-element-3359355{width:100%}}@media (max-width:1024px){.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide{height:420px}.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide-contents{max-width:100%}.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide-inner{padding:20px 20px 20px 20px}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-slide-heading{font-size:32px;line-height:1em;letter-spacing:1.5px}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-slide-description{font-size:25px}.elementor-9 .elementor-element.elementor-element-8bba405>.elementor-widget-container{margin:0px 0px 0px 0px;padding:0px 0px 0px 0px}.elementor-9 .elementor-element.elementor-element-7567ea3>.elementor-column-wrap>.elementor-widget-wrap>.elementor-widget:not(.elementor-widget__width-auto):not(.elementor-widget__width-initial):not(:last-child):not(.elementor-absolute){margin-bottom:0px}.elementor-9 .elementor-element.elementor-element-d6d7125>.elementor-widget-container{margin:0px 0px 0px 0px;padding:0px 0px 0px 0px}}@media (max-width:767px){.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide{height:360px}.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide-contents{max-width:100%}.elementor-9 .elementor-element.elementor-element-8bba405 .swiper-slide-inner{padding:5px 5px 5px 5px}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-slide-heading{font-size:25px;line-height:1em;letter-spacing:0.5px}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-slide-description{font-size:20px}.elementor-9 .elementor-element.elementor-element-8bba405 .elementor-slide-button{font-size:15px}.elementor-9 .elementor-element.elementor-element-8bba405>.elementor-widget-container{margin:0px 0px 0px 0px;padding:0px 0px 0px 0px}.elementor-9 .elementor-element.elementor-element-8bba405{width:100%;max-width:100%}.elementor-9 .elementor-element.elementor-element-d6d7125.elementor-wc-products .attachment-woocommerce_thumbnail{border-radius:0px 0px 0px 0px}.elementor-9 .elementor-element.elementor-element-d6d7125>.elementor-widget-container{margin:0px 0px 0px 0px}}html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}body{margin:0}header,main,section{display:block}a{background-color:transparent}strong{font-weight:inherit}strong{font-weight:bolder}img{border-style:none}button,input{font:inherit}button,input{overflow:visible}button{text-transform:none}button,[type=submit]{-webkit-appearance:button}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}button:-moz-focusring,input:-moz-focusring{outline:1px dotted ButtonText}[type=checkbox]{-webkit-box-sizing:border-box;box-sizing:border-box;padding:0}[type=search]{-webkit-appearance:textfield}[type=search]::-webkit-search-cancel-button,[type=search]::-webkit-search-decoration{-webkit-appearance:none}*,*:before,*:after{-webkit-box-sizing:border-box;box-sizing:border-box}html{-webkit-box-sizing:border-box;box-sizing:border-box;background-attachment:fixed}body{color:#777;scroll-behavior:smooth;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}img{max-width:100%;height:auto;display:inline-block;vertical-align:middle}a,button,input{-ms-touch-action:manipulation;touch-action:manipulation}.col{position:relative;margin:0;padding:0 15px 30px;width:100%}.col-inner{position:relative;margin-left:auto;margin-right:auto;width:100%;background-position:50% 50%;background-size:cover;background-repeat:no-repeat;-webkit-box-flex:1;-ms-flex:1 0 auto;flex:1 0 auto}@media screen and (min-width:850px){.col:first-child .col-inner{margin-left:auto;margin-right:0}.col+.col .col-inner{margin-right:auto;margin-left:0}}@media screen and (max-width:849px){.col{padding-bottom:30px}}.align-equal>.col{display:-webkit-box;display:-ms-flexbox;display:flex}.small-12{max-width:100%;-ms-flex-preferred-size:100%;flex-basis:100%}.small-columns-2>.col{max-width:50%;-ms-flex-preferred-size:50%;flex-basis:50%}@media screen and (min-width:550px){.medium-6{max-width:50%;-ms-flex-preferred-size:50%;flex-basis:50%}.medium-12{max-width:100%;-ms-flex-preferred-size:100%;flex-basis:100%}.medium-columns-3>.col{max-width:33.3333333333%;-ms-flex-preferred-size:33.3333333333%;flex-basis:33.3333333333%}}@media screen and (min-width:850px){.large-6{max-width:50%;-ms-flex-preferred-size:50%;flex-basis:50%}.large-columns-4>.col{max-width:25%;-ms-flex-preferred-size:25%;flex-basis:25%}}.has-shadow>.col>.col-inner{background-color:#fff}body,.container,.row{width:100%;margin-left:auto;margin-right:auto}.container{padding-left:15px;padding-right:15px}.container,.row{max-width:1080px}.row.row-collapse{max-width:1050px}.row.row-small{max-width:1065px}.flex-row{-js-display:flex;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-orient:horizontal;-webkit-box-direction:normal;-ms-flex-flow:row nowrap;flex-flow:row nowrap;-webkit-box-align:center;-ms-flex-align:center;align-items:center;-webkit-box-pack:justify;-ms-flex-pack:justify;justify-content:space-between;width:100%}.header .flex-row{height:100%}.flex-col{max-height:100%}.flex-grow{-webkit-box-flex:1;-ms-flex:1;flex:1;-ms-flex-negative:1;-ms-flex-preferred-size:auto!important}.flex-left{margin-right:auto}.flex-right{margin-left:auto}@media all and (-ms-high-contrast:none){.nav>li>a>i{top:-1px}}.row{width:100%;-js-display:flex;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-orient:horizontal;-webkit-box-direction:normal;-ms-flex-flow:row wrap;flex-flow:row wrap}.row-collapse{padding:0}.row-collapse>.col{padding:0!important}.row-small>.col{padding:0 9.8px 19.6px;margin-bottom:0}.nav-dropdown{position:absolute;min-width:260px;max-height:0;z-index:9;padding:20px 0 20px;opacity:0;margin:0;color:#777;background-color:#fff;text-align:left;display:table;left:-99999px}.nav-dropdown:after{visibility:hidden;display:block;content:"";clear:both;height:0}.nav-dropdown li{display:block;margin:0;vertical-align:top}.nav-dropdown>li.html{min-width:260px}.nav-dropdown>li>a{width:auto;display:block;padding:10px 20px;line-height:1.3}.nav-dropdown>li:last-child:not(.nav-dropdown-col)>a{border-bottom:0!important}.nav-dropdown.nav-dropdown-bold>li>a{margin:0 10px;padding-left:10px;border-radius:10px;padding-right:5px}.nav-dropdown.nav-dropdown-bold li.html{padding:0 20px 10px}.menu-item-has-block .nav-dropdown{display:block;padding:0}.nav-dropdown-has-arrow li.has-dropdown:after,.nav-dropdown-has-arrow li.has-dropdown:before{bottom:-2px;z-index:10;opacity:0;left:50%;border:solid transparent;content:"";height:0;width:0;position:absolute}.nav-dropdown-has-arrow li.has-dropdown:after{border-color:rgba(221,221,221,0);border-bottom-color:#fff;border-width:8px;margin-left:-8px}.nav-dropdown-has-arrow li.has-dropdown:before{z-index:-999;border-width:11px;margin-left:-11px}.nav-dropdown-has-arrow li.has-dropdown.menu-item-design-container-width:after,.nav-dropdown-has-arrow li.has-dropdown.menu-item-design-container-width:before{display:none}.nav-dropdown-has-shadow .nav-dropdown{-webkit-box-shadow:1px 1px 15px rgba(0,0,0,.15);box-shadow:1px 1px 15px rgba(0,0,0,.15)}.nav-dropdown-has-arrow.nav-dropdown-has-border li.has-dropdown:before{border-bottom-color:#ddd}.nav-dropdown-has-border .nav-dropdown{border:2px solid #ddd}.label-new.menu-item>a:after,.label-hot.menu-item>a:after,.label-sale.menu-item>a:after,.label-popular.menu-item>a:after{content:"";display:inline-block;font-size:9px;line-height:9px;text-transform:uppercase;letter-spacing:-0.1px;margin-left:4px;background-color:#000;font-weight:bolder;border-radius:2px;color:#fff;padding:2px 3px 3px;position:relative;top:-2px}.label-new.menu-item>a:after{background-color:#446084}.label-sale.menu-item>a:after{background-color:#d26e4b}.label-popular.menu-item>a:after{background-color:#7a9c59}.label-hot.menu-item>a:after{background-color:#b20000}.nav p{margin:0;padding-bottom:0}.nav,.nav ul:not(.nav-dropdown){margin:0;padding:0}.nav{width:100%;position:relative;display:inline-block;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-orient:horizontal;-webkit-box-direction:normal;-ms-flex-flow:row wrap;flex-flow:row wrap;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.nav>li{display:inline-block;list-style:none;margin:0;padding:0;position:relative;margin:0 7px}.nav>li>a{padding:10px 0;display:inline-block;display:-webkit-inline-box;display:-ms-inline-flexbox;display:inline-flex;-ms-flex-wrap:wrap;flex-wrap:wrap;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.nav-left{-webkit-box-pack:start;-ms-flex-pack:start;justify-content:flex-start}.nav-right{-webkit-box-pack:end;-ms-flex-pack:end;justify-content:flex-end}.nav>li>a,.nav-dropdown>li>a{color:rgba(102,102,102,.85)}.nav-dropdown>li>a{display:block}.nav>li.active>a{color:rgba(17,17,17,.85)}.nav li:first-child{margin-left:0!important}.nav li:last-child{margin-right:0!important}.nav-uppercase>li>a{letter-spacing:.02em;text-transform:uppercase;font-weight:bolder}li.html form,li.html input{margin:0}.nav.nav-vertical{-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-flow:column;flex-flow:column}.nav.nav-vertical li{list-style:none;margin:0;width:100%}.nav-vertical li li{font-size:1em;padding-left:.5em}.nav-vertical>li{display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-orient:horizontal;-webkit-box-direction:normal;-ms-flex-flow:row wrap;flex-flow:row wrap;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.nav-vertical>li ul{width:100%}.nav-vertical li li.menu-item-has-children{margin-bottom:1em}.nav-vertical>li>ul>li a,.nav-vertical>li>a{display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-align:center;-ms-flex-align:center;align-items:center;width:auto;-webkit-box-flex:1;-ms-flex-positive:1;flex-grow:1}.nav-vertical li li.menu-item-has-children>a{color:#000;text-transform:uppercase;font-size:.8em;font-weight:bolder}.nav-vertical>li.html{padding-top:1em;padding-bottom:1em}.nav-vertical>li>ul li a{color:#666}.nav-vertical>li>ul{margin:0 0 2em;padding-left:1em}.nav .children{position:fixed;opacity:0;left:-99999px;-webkit-transform:translateX(-10px);-ms-transform:translateX(-10px);transform:translateX(-10px)}.nav-sidebar.nav-vertical>li+li{border-top:1px solid #ececec}.nav-vertical>li+li{border-top:1px solid #ececec}.nav-vertical .social-icons{display:block;width:100%}.badge-container{margin:30px 0 0 0}.box{width:100%;position:relative;margin:0 auto}.box a{display:inline-block}.box-image>div>a{display:block}.box-text{padding-top:.7em;padding-bottom:1.4em;position:relative;width:100%;font-size:.9em}@media (max-width:549px){.box-text{font-size:85%}}.box-image{position:relative;height:auto;margin:0 auto;overflow:hidden}.box-text.text-center{padding-left:10px;padding-right:10px}.box-image img{max-width:100%;width:100%;margin:0 auto}.button,button{position:relative;display:inline-block;background-color:transparent;text-transform:uppercase;font-size:.97em;letter-spacing:.03em;font-weight:bolder;text-align:center;color:currentColor;text-decoration:none;border:1px solid transparent;vertical-align:middle;border-radius:0;margin-top:0;margin-right:1em;text-shadow:none;line-height:2.4em;min-height:2.5em;padding:0 1.2em;max-width:100%;text-rendering:optimizeLegibility;-webkit-box-sizing:border-box;box-sizing:border-box}.button{color:#fff;background-color:#446084;background-color:var(--primary-color);border-color:rgba(0,0,0,.05)}.secondary{background-color:#d26e4b}.flex-col button,.flex-col .button,.flex-col input{margin-bottom:0}.is-divider{height:3px;display:block;background-color:rgba(0,0,0,.1);margin:1em 0 1em;width:100%;max-width:30px}form{margin-bottom:0}input[type=search],input[type=text],input[type=password]{-webkit-box-sizing:border-box;box-sizing:border-box;border:1px solid #ddd;padding:0 .75em;height:2.507em;font-size:.97em;border-radius:0;max-width:100%;width:100%;vertical-align:middle;background-color:#fff;color:#333;-webkit-box-shadow:inset 0 1px 2px rgba(0,0,0,.1);box-shadow:inset 0 1px 2px rgba(0,0,0,.1)}input[type=search],input[type=text]{-webkit-appearance:none;-moz-appearance:none;appearance:none}label{font-weight:bold;display:block;font-size:.9em;margin-bottom:.4em}input[type=checkbox]{display:inline;margin-right:10px;font-size:16px}i[class^=icon-],i[class*=" icon-"]{font-family:"fl-icons"!important;font-display:block;speak:none!important;margin:0;padding:0;display:inline-block;font-style:normal!important;font-weight:normal!important;font-variant:normal!important;text-transform:none!important;position:relative;line-height:1.2}button i,.button i{vertical-align:middle;top:-1.5px}a.icon:not(.button){font-family:sans-serif;margin-left:.25em;margin-right:.25em;font-size:1.2em}.button.icon{margin-left:.12em;margin-right:.12em;min-width:2.5em;padding-left:.6em;padding-right:.6em;display:inline-block}.button.icon i{font-size:1.2em}.nav>li>a>i{vertical-align:middle;font-size:20px}.nav>li>a>i.icon-search{font-size:1.2em}.nav>li>a>i.icon-menu{font-size:1.9em}.nav>li.has-icon>a>i{min-width:1em}.has-dropdown .icon-angle-down{font-size:16px;margin-left:.2em;opacity:.6}.image-icon{display:inline-block;height:auto;vertical-align:middle;position:relative}span+.image-icon{margin-left:10px}img{opacity:1}.image-tools{padding:10px;position:absolute}.image-tools.top.right{padding-bottom:0;padding-left:0}@media only screen and (max-device-width:1024px){.image-tools{opacity:1!important;padding:5px}}.lightbox-content{background-color:#fff;max-width:875px;margin:0 auto;-webkit-box-shadow:3px 3px 20px 0 rgba(0,0,0,.15);box-shadow:3px 3px 20px 0 rgba(0,0,0,.15);position:relative}.lightbox-content .lightbox-inner{padding:30px 20px}.mfp-hide{display:none!important}.ux-menu-link{-webkit-box-align:center;-ms-flex-align:center;align-items:center}.dark .ux-menu-link__link{border-bottom-color:rgba(255,255,255,.2)}.ux-menu.ux-menu--divider-solid .ux-menu-link:not(:last-of-type) .ux-menu-link__link{border-bottom-style:solid}.ux-menu-link__link{-webkit-box-flex:1;-ms-flex:1;flex:1;min-height:2.5em;-webkit-box-align:baseline;-ms-flex-align:baseline;align-items:baseline;padding-top:.3em;padding-bottom:.3em;color:currentColor;border-bottom-color:#ececec;border-bottom-width:1px}.ux-menu-link__icon{width:16px;-ms-flex-negative:0;flex-shrink:0;vertical-align:middle}.ux-menu-link__icon+.ux-menu-link__text{padding-left:.5em}.stack{--stack-gap:0;-js-display:flex;display:-webkit-box;display:-ms-flexbox;display:flex}.stack-col{-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column}.stack-col>*{margin:0!important}.stack-col>*~*{margin-top:var(--stack-gap)!important}.justify-start{-webkit-box-pack:start;-ms-flex-pack:start;justify-content:flex-start}label{color:#222}a{color:#334862;text-decoration:none}a.plain{color:currentColor}.dark a{color:currentColor}ul{list-style:disc}ul{margin-top:0;padding:0}ul ul{margin:1.5em 0 1.5em 3em}li{margin-bottom:.6em}.button,button,input{margin-bottom:1em}form,p,ul{margin-bottom:1.3em}form p{margin-bottom:.5em}body{line-height:1.6}h1,h2,h3,h4{color:#555;width:100%;margin-top:0;margin-bottom:.5em;text-rendering:optimizeSpeed}h1{font-size:1.7em;line-height:1.3}h2{font-size:1.6em;line-height:1.3}h3{font-size:1.25em}h4{font-size:1.125em}@media (max-width:549px){h1{font-size:1.4em}h2{font-size:1.2em}h3{font-size:1em}}p{margin-top:0}.uppercase{line-height:1.05;letter-spacing:.05em;text-transform:uppercase}.is-normal{font-weight:normal}.uppercase{line-height:1.2;text-transform:uppercase}.is-small{font-size:.8em}.box-text h4{line-height:1.3;margin-top:.1em;margin-bottom:.1em}.nav>li>a{font-size:.8em}.nav>li.html{font-size:.85em}.container:after,.row:after{content:"";display:table;clear:both}@media (min-width:850px){.show-for-medium{display:none!important}}@media (max-width:849px){.hide-for-medium{display:none!important}}.full-width{width:100%!important;max-width:100%!important;padding-left:0!important;padding-right:0!important;display:block}.mb-0{margin-bottom:0!important}.ml-0{margin-left:0!important}.inner-padding{padding:30px}.text-left{text-align:left}.text-center{text-align:center}.text-center>div,.text-center>div>div,.text-center .is-divider{margin-left:auto;margin-right:auto}.relative{position:relative!important}.absolute{position:absolute!important}.top{top:0}.right{right:0}.left{left:0}.fill{position:absolute;top:0;left:0;height:100%;right:0;bottom:0;padding:0!important;margin:0!important}.z-1{z-index:21}.z-top{z-index:9995}.flex{display:-webkit-box;display:-ms-flexbox;display:flex;-js-display:flex}.no-scrollbar{-ms-overflow-style:-ms-autohiding-scrollbar;scrollbar-width:none}.no-scrollbar::-webkit-scrollbar{width:0px!important;height:0px!important}.screen-reader-text{clip:rect(1px,1px,1px,1px);position:absolute!important;height:1px;width:1px;overflow:hidden}.has-shadow .box:not(.box-overlay):not(.box-shade){background-color:#fff}.row-box-shadow-2 .col-inner{-webkit-box-shadow:0 3px 6px -4px rgba(0,0,0,.16),0 3px 6px rgba(0,0,0,.23);box-shadow:0 3px 6px -4px rgba(0,0,0,.16),0 3px 6px rgba(0,0,0,.23)}.show-on-hover{opacity:0;-webkit-filter:blur(0);filter:blur(0)}.dark{color:#f1f1f1}.dark h2,.dark h4{color:#fff}html{overflow-x:hidden}@media (max-width:849px){body{overflow-x:hidden}}#wrapper,#main{background-color:#fff;position:relative}.header,.header-wrapper{width:100%;z-index:30;position:relative;background-size:cover;background-position:50% 0}.header-bg-color{background-color:rgba(255,255,255,.9)}.header-bg-image,.header-bg-color{background-position:50% 0}.header-main{z-index:10;position:relative}.top-divider{margin-bottom:-1px;border-top:1px solid currentColor;opacity:.1}.nav>li.header-divider{border-left:1px solid rgba(0,0,0,.1);height:30px;vertical-align:middle;position:relative;margin:0 7.5px}html{background-color:#5b5b5b}.logo{line-height:1;margin:0}.logo a{text-decoration:none;display:block;color:#446084;font-size:32px;text-transform:uppercase;font-weight:bolder;margin:0}.logo img{display:block;width:auto}.header-logo-dark{display:none!important}.logo-left .logo{margin-left:0;margin-right:30px}@media screen and (max-width:849px){.header-inner .nav{-ms-flex-wrap:nowrap;flex-wrap:nowrap}.medium-logo-center .flex-left{-webkit-box-ordinal-group:2;-ms-flex-order:1;order:1;-webkit-box-flex:1;-ms-flex:1 1 0px;flex:1 1 0}.medium-logo-center .logo{-webkit-box-ordinal-group:3;-ms-flex-order:2;order:2;text-align:center;margin:0 15px}.medium-logo-center .logo img{margin:0 auto}.medium-logo-center .flex-right{-webkit-box-flex:1;-ms-flex:1 1 0px;flex:1 1 0;-webkit-box-ordinal-group:4;-ms-flex-order:3;order:3}}.sidebar-menu .search-form{display:block!important}.searchform-wrapper form{margin-bottom:0}.sidebar-menu .search-form{padding:5px 0;width:100%}.searchform-wrapper:not(.form-flat) .submit-button{border-top-left-radius:0!important;border-bottom-left-radius:0!important}.searchform{position:relative}.searchform .button.icon{margin:0}.searchform .button.icon i{font-size:1.2em}.searchform-wrapper{width:100%}.header .search-form .live-search-results{text-align:left;color:#111;top:105%;-webkit-box-shadow:0 0 10px 0 rgba(0,0,0,.1);box-shadow:0 0 10px 0 rgba(0,0,0,.1);left:0;right:0;background-color:rgba(255,255,255,.95);position:absolute}.header li .html .live-search-results{top:0;position:relative;-webkit-box-shadow:none;box-shadow:none;background-color:transparent}.icon-menu:before{content:""}.icon-angle-right:before{content:""}.icon-angle-down:before{content:""}.icon-twitter:before{content:""}.icon-envelop:before{content:""}.icon-facebook:before{content:""}.icon-instagram:before{content:""}.icon-pinterest:before{content:""}.icon-search:before{content:""}.icon-linkedin:before{content:""}.icon-youtube:before{content:""}.social-icons{display:inline-block;vertical-align:middle;font-size:.85em;color:#999}.html .social-icons{font-size:1em}.social-icons i{min-width:1em}.woocommerce-form-login .button{margin-bottom:0}p.form-row-wide{clear:both}span.amount{white-space:nowrap;color:#111;font-weight:bold}.header-cart-title span.amount{color:currentColor}.cart-icon{display:inline-block}.cart-icon strong{border-radius:0;font-weight:bold;margin:.3em 0;border:2px solid #446084;color:#446084;position:relative;display:inline-block;vertical-align:middle;text-align:center;width:2.2em;height:2.2em;font-size:1em;line-height:1.9em;font-family:Helvetica,Arial,Sans-serif}.cart-icon strong:after{bottom:100%;margin-bottom:0;margin-left:-7px;height:8px;width:14px;left:50%;content:" ";position:absolute;border:2px solid #446084;border-top-left-radius:99px;border-top-right-radius:99px;border-bottom:0}.woocommerce-mini-cart__empty-message{text-align:center}</style><link rel="preload" href="https://remcuahn.com/wp-content/cache/min/1/04fa7a1cb8a91438ab32cb19ec945497.css" data-rocket-async="style" as="style" onload="this.onload=null;this.rel='stylesheet'" media="all" data-minify="1" />
	<meta name="description" content="Mẫu rèm vải, màn cửa sổ, cửa đi đẹp, sang trọng, hiện đại cho phòng khách, phòng ngủ, phòng thờ, Bếp ăn - Thanh Nhàn cung cấp giải pháp rèm gia đình, văn phòng" />
	<link rel="canonical" href="https://remcuahn.com/" />
	<meta property="og:locale" content="vi_VN" />
	<meta property="og:type" content="website" />
	<meta property="og:title" content="Rèm cửa đi, cửa sổ phòng khách, phòng ngủ đẹp, giá rẻ" />
	<meta property="og:description" content="Mẫu rèm vải, màn cửa sổ, cửa đi đẹp, sang trọng, hiện đại cho phòng khách, phòng ngủ, phòng thờ, Bếp ăn - Thanh Nhàn cung cấp giải pháp rèm gia đình, văn phòng" />
	<meta property="og:url" content="https://remcuahn.com/" />
	<meta property="og:site_name" content="remcuahn.com" />
	<meta property="article:publisher" content="https://www.facebook.com/remthanhnhanhn/" />
	<meta property="article:modified_time" content="2021-09-11T16:47:56+00:00" />
	<meta property="og:image" content="https://remcuahn.com/wp-content/uploads/2021/04/remcuahn.jpg" />
	<meta property="og:image:width" content="680" />
	<meta property="og:image:height" content="510" />
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:site" content="@remthanhnhanvn" />
	<meta name="twitter:label1" content="Ước tính thời gian đọc" />
	<meta name="twitter:data1" content="4 phút" />
	<script type="application/ld+json" class="yoast-schema-graph">{"@context":"https://schema.org","@graph":[{"@type":["Organization","Place","Corporation"],"@id":"https://remcuahn.com/#organization","name":"Cty c\u1ed5 ph\u1ea7n X\u00e2y d\u1ef1ng v\u00e0 N\u1ed9i th\u1ea5t Thanh Nh\u00e0n","url":"https://remcuahn.com/","sameAs":["https://www.facebook.com/remthanhnhanhn/","https://www.instagram.com/remthanhnhanvn/","https://www.linkedin.com/in/remthanhnhanvn/","https://www.youtube.com/channel/UC-7eesq6KpLBkfpxjcYhe6Q","https://www.pinterest.com/remthanhnhanvn/","http://wikimapia.org/40964152/vi/R\u00e8m-C\u1eeda-Thanh-Nh\u00e0n-C\u00f4ng-ty-c\u1ed5-ph\u1ea7n-X\u00e2y-d\u1ef1ng-v\u00e0-N\u1ed9i-th\u1ea5t-Thanh-Nh\u00e0n","https://twitter.com/remthanhnhanvn"],"logo":{"@type":"ImageObject","@id":"https://remcuahn.com/#logo","inLanguage":"vi","url":"https://remcuahn.com/wp-content/uploads/2021/08/cropped-logo2018.png","contentUrl":"https://remcuahn.com/wp-content/uploads/2021/08/cropped-logo2018.png","width":225,"height":225,"caption":"Cty c\u1ed5 ph\u1ea7n X\u00e2y d\u1ef1ng v\u00e0 N\u1ed9i th\u1ea5t Thanh Nh\u00e0n"},"image":{"@id":"https://remcuahn.com/#logo"},"location":{"@id":"https://remcuahn.com/#local-place"},"address":{"@id":"https://remcuahn.com/#local-place-address"},"email":"quangr77@gmail.com","telephone":"024 3201 2676"},{"@type":"WebSite","@id":"https://remcuahn.com/#website","url":"https://remcuahn.com/","name":"remcuahn.com","description":"M\u1eabu m\u00e0nh r\u00e8m c\u1eeda \u0111\u1eb9p","publisher":{"@id":"https://remcuahn.com/#organization"},"potentialAction":[{"@type":"SearchAction","target":{"@type":"EntryPoint","urlTemplate":"https://remcuahn.com/?s={search_term_string}"},"query-input":"required name=search_term_string"}],"inLanguage":"vi"},{"@type":"WebPage","@id":"https://remcuahn.com/#webpage","url":"https://remcuahn.com/","name":"R\u00e8m c\u1eeda \u0111i, c\u1eeda s\u1ed5 ph\u00f2ng kh\u00e1ch, ph\u00f2ng ng\u1ee7 \u0111\u1eb9p, gi\u00e1 r\u1ebb - remcuahn.com","isPartOf":{"@id":"https://remcuahn.com/#website"},"about":{"@id":"https://remcuahn.com/#organization"},"datePublished":"2021-08-23T11:56:22+00:00","dateModified":"2021-09-11T16:47:56+00:00","description":"M\u1eabu r\u00e8m v\u1ea3i, m\u00e0n c\u1eeda s\u1ed5, c\u1eeda \u0111i \u0111\u1eb9p, sang tr\u1ecdng, hi\u1ec7n \u0111\u1ea1i cho ph\u00f2ng kh\u00e1ch, ph\u00f2ng ng\u1ee7, ph\u00f2ng th\u1edd, B\u1ebfp \u0103n - Thanh Nh\u00e0n cung c\u1ea5p gi\u1ea3i ph\u00e1p r\u00e8m gia \u0111\u00ecnh, v\u0103n ph\u00f2ng","breadcrumb":{"@id":"https://remcuahn.com/#breadcrumb"},"inLanguage":"vi","potentialAction":[{"@type":"ReadAction","target":["https://remcuahn.com/"]}]},{"@type":"BreadcrumbList","@id":"https://remcuahn.com/#breadcrumb","itemListElement":[{"@type":"ListItem","position":1,"name":"Trang ch\u1ee7"}]},{"@type":"Place","@id":"https://remcuahn.com/#local-place","address":{"@type":"PostalAddress","@id":"https://remcuahn.com/#local-place-address","streetAddress":"LK-323, DV-14, \u0110\u1ea5t d\u1ecbc v\u1ee5 H\u00f2a B\u00ecnh Ph\u01b0\u1eddng Y\u00ean Ngh\u0129a, H\u00e0 \u0110\u00f4ng, H\u00e0 N\u1ed9i","addressLocality":"H\u00e0 N\u1ed9i","postalCode":"100000","addressRegion":"H\u00e0 N\u1ed9i","addressCountry":"VN"},"geo":{"@type":"GeoCoordinates","latitude":"20.9568158","longitude":"105.741188"},"openingHoursSpecification":[{"@type":"OpeningHoursSpecification","dayOfWeek":["Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"],"opens":"07:00","closes":"21:30"}],"telephone":"024 3201 2676"}]}</script>
	<meta name="msvalidate.01" content="9C04AB30F6BBA1FA4080B78891C37824" />
	<meta name="google-site-verification" content="J4LscFAnAw3o4wpYA2h_JHQtAO19guohKWuI7j_JjNE" />
	<meta name="p:domain_verify" content="5a753666074e99776e162249871751bd" />
	<meta name="yandex-verification" content="fd67a7e3e559138a" />
	<meta name="geo.placename" content="Hà Nội" />
	<meta name="geo.position" content="20.9568158;105.741188" />
	<meta name="geo.region" content="Việt Nam" />
	<!-- / Yoast SEO Premium plugin. -->


<link rel='dns-prefetch' href='//fonts.googleapis.com' />
<link rel='dns-prefetch' href='//fonts.gstatic.com' />
<link rel='dns-prefetch' href='//connect.facebook.net' />
<link rel='dns-prefetch' href='//www.facebook.com' />
<link href='https://fonts.gstatic.com' crossorigin rel='preconnect' />
<link rel="alternate" type="application/rss+xml" title="Dòng thông tin remcuahn.com &raquo;" href="https://remcuahn.com/feed/" />
<link rel="alternate" type="application/rss+xml" title="Dòng phản hồi remcuahn.com &raquo;" href="https://remcuahn.com/comments/feed/" />




<style id='woocommerce-inline-inline-css' type='text/css'>
.woocommerce form .form-row .required { visibility: visible; }
</style>


<style id='flatsome-main-inline-css' type='text/css'>
@font-face {
				font-family: "fl-icons";
				font-display: block;
				src: url(https://remcuahn.com/wp-content/themes/flatsome/assets/css/icons/fl-icons.eot?v=3.14.2);
				src:
					url(https://remcuahn.com/wp-content/themes/flatsome/assets/css/icons/fl-icons.eot#iefix?v=3.14.2) format("embedded-opentype"),
					url(https://remcuahn.com/wp-content/themes/flatsome/assets/css/icons/fl-icons.woff2?v=3.14.2) format("woff2"),
					url(https://remcuahn.com/wp-content/themes/flatsome/assets/css/icons/fl-icons.ttf?v=3.14.2) format("truetype"),
					url(https://remcuahn.com/wp-content/themes/flatsome/assets/css/icons/fl-icons.woff?v=3.14.2) format("woff"),
					url(https://remcuahn.com/wp-content/themes/flatsome/assets/css/icons/fl-icons.svg?v=3.14.2#fl-icons) format("svg");
			}
</style>


<link rel='preload'   href='//fonts.googleapis.com/css?family=Lato%3Aregular%2C700%2C400%2C700%7CDancing+Script%3Aregular%2C400&#038;display=swap&#038;ver=3.9' data-rocket-async="style" as="style" onload="this.onload=null;this.rel='stylesheet'" type='text/css' media='all' />
<script type="rocketlazyloadscript" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-includes/js/jquery/jquery.min.js?ver=3.5.1' id='jquery-core-js' defer></script>
<script type="rocketlazyloadscript" data-minify="1" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-content/cache/min/1/wp-content/plugins/wp-helper-lite/public/partials/assets/js/mbwph-scripts.js?ver=1631963618' id='mfb-script-js' defer></script>
<link rel="https://api.w.org/" href="https://remcuahn.com/wp-json/" /><link rel="alternate" type="application/json" href="https://remcuahn.com/wp-json/wp/v2/pages/3229" /><link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://remcuahn.com/xmlrpc.php?rsd" />
<link rel="wlwmanifest" type="application/wlwmanifest+xml" href="https://remcuahn.com/wp-includes/wlwmanifest.xml" /> 
<meta name="generator" content="WordPress 5.7.2" />
<meta name="generator" content="WooCommerce 5.5.2" />
<link rel='shortlink' href='https://remcuahn.com/' />
<!-- site-navigation-element Schema optimized by Schema Pro --><script type="application/ld+json">{"@context":"https:\/\/schema.org","@graph":[{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"Trang Ch\u1ee7","url":"https:\/\/remcuahn.com\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m C\u1eeda","url":"https:\/\/remcuahn.com\/rem-cua\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m V\u1ea3i","url":"https:\/\/remcuahn.com\/danh-muc\/rem-vai\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m V\u1ea3i M\u1ed9t M\u00e0u","url":"https:\/\/remcuahn.com\/danh-muc\/rem-vai\/rem-vai-mot-mau\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m V\u1ea3i Hoa V\u0103n","url":"https:\/\/remcuahn.com\/danh-muc\/rem-vai\/rem-vai-hoa-van\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m V\u1ea3i Cao C\u1ea5p","url":"https:\/\/remcuahn.com\/danh-muc\/rem-vai\/rem-vai-cao-cap\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m V\u1ea3i Gi\u00e1 R\u1ebb","url":"https:\/\/remcuahn.com\/danh-muc\/rem-vai\/rem-vai-gia-re\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m Roman","url":"https:\/\/remcuahn.com\/danh-muc\/rem-roman\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m G\u1ed7 - M\u00e0nh G\u1ed7","url":"https:\/\/remcuahn.com\/danh-muc\/rem-go\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m C\u1ea7u V\u1ed3ng","url":"https:\/\/remcuahn.com\/danh-muc\/rem-cau-vong\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m Cu\u1ed1n - M\u00e0n Cu\u1ed1n","url":"https:\/\/remcuahn.com\/danh-muc\/rem-cuon\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m Cu\u1ed1n Tranh","url":"https:\/\/remcuahn.com\/danh-muc\/rem-cuon-tranh\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m L\u00e1 D\u1ecdc","url":"https:\/\/remcuahn.com\/danh-muc\/rem-la-doc\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m S\u00e1o Nh\u00f4m","url":"https:\/\/remcuahn.com\/danh-muc\/rem-sao-nhom\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m Ng\u0103n L\u1ea1nh \u0110i\u1ec1u H\u00f2a","url":"https:\/\/remcuahn.com\/danh-muc\/rem-vai\/rem-ngan-lanh-dieu-hoa\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu R\u00e8m H\u1ea1t G\u1ed7","url":"https:\/\/remcuahn.com\/danh-muc\/mau-rem-hat-go\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"T\u01b0 V\u1ea5n R\u00e8m C\u1eeda","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m C\u1eeda Roman","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/rem-roman\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u00e0n R\u00e8m V\u1ea3i 2 L\u1edbp","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/man-rem-vai-2-lop\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m V\u1ea3i M\u1ed9t M\u00e0u","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/rem-vai-mot-mau\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m C\u1eeda Cao C\u1ea5p","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/rem-cua-cao-cap\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m \u0110\u1eb9p Gi\u00e1 R\u1ebb","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/rem-dep-gia-re\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m Ng\u0103n Ph\u00f2ng \u0110i\u1ec1u H\u00f2a","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/rem-ngan-phong-dieu-hoa\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m C\u1eeda C\u1ea7u V\u1ed3ng","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/rem-cau-vong\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m S\u00e1o G\u1ed7","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/rem-go\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m C\u1eeda Cu\u1ed1n","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/rem-cuon\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m C\u1eeda L\u00e1 D\u1ecdc","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/rem-la-doc\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u00e0n S\u00e1o Nh\u00f4m","url":"https:\/\/remcuahn.com\/tu-van-rem-cua\/man-sao-nhom\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m h\u1ea1t g\u1ed7 phong th\u1ee7y","url":"https:\/\/remcuahn.com\/rem-hat-go-phong-thuy\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"Tin T\u1ee9c","url":"https:\/\/remcuahn.com\/tin-tuc\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"R\u00e8m c\u1eeda s\u1ed5 \u0111\u1eb9p","url":"https:\/\/remcuahn.com\/mau-rem-cua-so-dep-bao-gia-nam-2020\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"M\u1eabu r\u00e8m ROMAN","url":"https:\/\/remcuahn.com\/mau-rem-roman-rem-xep-lop\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"Kh\u00e1ch H\u00e0ng","url":"https:\/\/remcuahn.com\/tin-tuc\/khach-hang\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"B\u00e1o Gi\u00e1","url":"https:\/\/remcuahn.com\/tin-tuc\/bao-gia\/"},{"@context":"https:\/\/schema.org","@type":"SiteNavigationElement","id":"site-navigation","name":"Li\u00ean H\u1ec7","url":"https:\/\/remcuahn.com\/lien-he\/"}]}</script><!-- / site-navigation-element Schema optimized by Schema Pro --><!--[if IE]><link rel="stylesheet" type="text/css" href="https://remcuahn.com/wp-content/themes/flatsome/assets/css/ie-fallback.css"><script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.6.1/html5shiv.js"></script><script>var head = document.getElementsByTagName('head')[0],style = document.createElement('style');style.type = 'text/css';style.styleSheet.cssText = ':before,:after{content:none !important';head.appendChild(style);setTimeout(function(){head.removeChild(style);}, 0);</script><script src="https://remcuahn.com/wp-content/themes/flatsome/assets/libs/ie-flexibility.js"></script><![endif]--><meta name="p:domain_verify" content="5a753666074e99776e162249871751bd"/>
<meta name="yandex-verification" content="fd67a7e3e559138a" />
<meta name="google-site-verification" content="J4LscFAnAw3o4wpYA2h_JHQtAO19guohKWuI7j_JjNE" />

<!-- Google Tag Manager -->
<script type="rocketlazyloadscript">(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-WCZLXS4');</script>
<!-- End Google Tag Manager -->

<script type="application/ld+json">
 { "@context": "https://schema.org",
 "@type": "Organization",
 "name": "Công ty cổ phần Xây dựng và Nội thất Thanh Nhàn",
 "legalName" : "THANH NHAN CONSTRUCTION AND FURNITURE .JSC",
 "url": "https://remcuahn.com/",
 "Brand": "https://remcuahn.com/wp-content/uploads/2021/02/cropped-logo-trong-suot.png ",
 "logo": "https://remcuahn.com/wp-content/uploads/2021/08/logo-300-100.png",
 "founders":  "Trần Văn Quảng",
 "foundingDate": "2018",
"sameAs": [ 
"https://www.facebook.com/RemCuaDep.ThanhNhan/",
"https://www.facebook.com/RemVaiDep.ThanhNhan/",
"https://twitter.com/remthanhnhanvn/",
"https://www.linkedin.com/in/remthanhnhanvn/",
"https://www.pinterest.com/remthanhnhanvn/",
"https://www.instagram.com/remcuahn/",
"https://www.youtube.com/channel/UC-7eesq6KpLBkfpxjcYhe6Q"
], 
"aggregateRating": {
    		"@type": "AggregateRating",
 			"ratingValue": "5",
 			"reviewCount": "200" 
	}
}
</script>
<script type='application/ld+json'>
{ "@context": "http://www.schema.org",
  "@type": "Store",
  "name": "Công ty cổ phần Xây dựng và Nội thất Thanh Nhàn",
  "url": "https://remcuahn.com/",
  "logo": "https://remcuahn.com/wp-content/uploads/2021/08/logo-300-100.png",
  "priceRange": "250.000",
  "image": "https://remcuahn.com/wp-content/uploads/2021/08/mau-rem-cua.jpg",
  "description": "Công ty cổ phần Xây dựng và Nội thất Thanh Nhàn là một đơn vị hàng đầu Việt Nam cung cấp và thi công các loại mành rèm cửa đẹp, chất lượng, uy tín, giá cạnh tranh tại Việt Nam.",
  "address": {
     "@type": "PostalAddress",
     "streetAddress": "LK-323, DV-14, Đất dịc vụ Hòa Bình Phường Yên Nghĩa",
     "addressLocality": "Hà Đông, Hà Nội",
     "addressRegion": "Hà Nội",
     "postalCode": "100000",
     "addressCountry": "Việt Nam"
  },
  "geo": {
     "@type": "GeoCoordinates",
     "latitude": "20,9568164",
     "longitude": "105,7411884"
  },
  "hasMap": "https://goo.gl/maps/pV69xhkfZENeGkru6",
   "openingHours": "Mo 07:00-21:30 Tu 07:00-21:30 We 07:00-21:30 Th 07:00-21:30 Fr 07:00-21:30 Sa 07:00-21:30 Su 07:00-21:30",
  "telephone": "091 211 99 01"
}
</script>
<script type="application/ld+json">
{ "@context" : "http://schema.org",
  "@type" : "LocalBusiness",
  "name" : "Công ty cổ phần Xây dựng và Nội thất Thanh Nhàn",
  "image" : "https://remcuahn.com/wp-content/uploads/2021/08/mau-rem-cua.jpg",
  "telephone" : "091 211 9901",
  "email" : "quangr77@gmail.com",
  "address": {
     "@type": "PostalAddress",
     "streetAddress": "LK-323, DV-14, Đất dịc vụ Hòa Bình Phường Yên Nghĩa",
     "addressLocality": "Hà Đông, Hà Nội",
     "addressRegion": "Hà Nội",
     "postalCode": "100000",
     "addressCountry": "Việt Nam"
  },
  "priceRange": "250.000",
  "url" : "https://remcuahn.com/"
}
</script>	<noscript><style>.woocommerce-product-gallery{ opacity: 1 !important; }</style></noscript>
				<style id="wpsp-style-frontend"></style>
			<link rel="icon" href="https://remcuahn.com/wp-content/uploads/2021/02/cropped-logo-trong-suot-32x32.png" sizes="32x32" />
<link rel="icon" href="https://remcuahn.com/wp-content/uploads/2021/02/cropped-logo-trong-suot-192x192.png" sizes="192x192" />
<link rel="apple-touch-icon" href="https://remcuahn.com/wp-content/uploads/2021/02/cropped-logo-trong-suot-180x180.png" />
<meta name="msapplication-TileImage" content="https://remcuahn.com/wp-content/uploads/2021/02/cropped-logo-trong-suot-270x270.png" />
<style id="custom-css" type="text/css">:root {--primary-color: #446084;}.full-width .ubermenu-nav, .container, .row{max-width: 1150px}.row.row-collapse{max-width: 1120px}.row.row-small{max-width: 1142.5px}.row.row-large{max-width: 1180px}.header-main{height: 101px}#logo img{max-height: 101px}#logo{width:200px;}.header-top{min-height: 30px}.transparent .header-main{height: 90px}.transparent #logo img{max-height: 90px}.has-transparent + .page-title:first-of-type,.has-transparent + #main > .page-title,.has-transparent + #main > div > .page-title,.has-transparent + #main .page-header-wrapper:first-of-type .page-title{padding-top: 90px;}.header.show-on-scroll,.stuck .header-main{height:70px!important}.stuck #logo img{max-height: 70px!important}.header-bottom {background-color: #f1f1f1}.header-main .nav > li > a{line-height: 16px }.stuck .header-main .nav > li > a{line-height: 50px }.header-bottom-nav > li > a{line-height: 16px }@media (max-width: 549px) {.header-main{height: 70px}#logo img{max-height: 70px}}.nav-dropdown{font-size:100%}/* Background Color */[data-icon-label]:after, .secondary.is-underline:hover,.secondary.is-outline:hover,.icon-label,.button.secondary:not(.is-outline),.button.alt:not(.is-outline), .badge-inner.on-sale, .button.checkout, .single_add_to_cart_button, .current .breadcrumb-step{ background-color:#ff0000; }[data-text-bg="secondary"]{background-color: #ff0000;}/* Color */.secondary.is-underline,.secondary.is-link, .secondary.is-outline,.stars a.active, .star-rating:before, .woocommerce-page .star-rating:before,.star-rating span:before, .color-secondary{color: #ff0000}/* Color !important */[data-text-color="secondary"]{color: #ff0000!important;}/* Border */.secondary.is-outline:hover{border-color:#ff0000}body{font-size: 100%;}@media screen and (max-width: 549px){body{font-size: 100%;}}body{font-family:"Lato", sans-serif}body{font-weight: 400}.nav > li > a {font-family:"Lato", sans-serif;}.mobile-sidebar-levels-2 .nav > li > ul > li > a {font-family:"Lato", sans-serif;}.nav > li > a {font-weight: 700;}.mobile-sidebar-levels-2 .nav > li > ul > li > a {font-weight: 700;}h1,h2,h3,h4,h5,h6,.heading-font, .off-canvas-center .nav-sidebar.nav-vertical > li > a{font-family: "Lato", sans-serif;}h1,h2,h3,h4,h5,h6,.heading-font,.banner h1,.banner h2{font-weight: 700;}.alt-font{font-family: "Dancing Script", sans-serif;}.alt-font{font-weight: 400!important;}@media screen and (min-width: 550px){.products .box-vertical .box-image{min-width: 247px!important;width: 247px!important;}}.absolute-footer, html{background-color: #bcbcbc}.page-title-small + main .product-container > .row{padding-top:0;}/* Custom CSS */.h1, h1 {font-size: 1.8em;font-weight: 600;}.h2, h2 {font-size: 1.5em;font-weight: 500;}.nav > li > a {font-weight: 500;font-size: .9em;}.h3, h3, h4, h5, h6 {font-size: 1.3em;font-weight: 500;}h1.page-title.is-large.uppercase{ display:none }.hotline-phone-ring-wrap{ position: fixed; bottom: 0; left: 0; z-index: 999999 }.hotline-phone-ring{ position: relative; visibility: visible; background-color: transparent; width: 200px; height: 200px; cursor: pointer; z-index: 11; -webkit-backface-visibility: hidden; -webkit-transform: translateZ(0); transition: visibility .5s; right: 150px; left: -50px; bottom: -50px; display: block }.hotline-phone-ring-circle{ width: 160px; height: 160px; top: 20px; left: 20px; position: absolute; background-color: transparent; border-radius: 100%; border: 2px solid #ff0000; -webkit-animation: phonering-alo-circle-anim 1.2s infinite ease-in-out; animation: phonering-alo-circle-anim 1.2s infinite ease-in-out; transition: all .5s; -webkit-transform-origin: 50% 50%; -ms-transform-origin: 50% 50%; transform-origin: 50% 50%; opacity: 0.5 }.hotline-phone-ring-circle-fill{ width: 100px; height: 100px; top: 50px; left: 50px; position: absolute; background-color: #ff4d4d; border-radius: 100%; border: 2px solid transparent; -webkit-animation: phonering-alo-circle-fill-anim 2.3s infinite ease-in-out; animation: phonering-alo-circle-fill-anim 2.3s infinite ease-in-out; transition: all .5s; -webkit-transform-origin: 50% 50%; -ms-transform-origin: 50% 50%; transform-origin: 50% 50% }.hotline-phone-ring-img-circle{ background-color: #ff0000; width: 55px; height: 55px; top: 72.5px; left: 72.5px; position: absolute; background-size: 20px; border-radius: 100%; border: 2px solid transparent; -webkit-animation: phonering-alo-circle-img-anim 1s infinite ease-in-out; animation: phonering-alo-circle-img-anim 1s infinite ease-in-out; -webkit-transform-origin: 50% 50%; -ms-transform-origin: 50% 50%; transform-origin: 50% 50%; display: -webkit-box; display: -webkit-flex; display: -ms-flexbox; display: flex; align-items: center; justify-content: center }.hotline-phone-ring-img-circle .pps-btn-img{ display: -webkit-box; display: -webkit-flex; display: -ms-flexbox; display: flex }.hotline-phone-ring-img-circle .pps-btn-img img{ width: 40px; height: 40px }.hotline-bar{ position: absolute; background: #ff0000; height: 40px; width: 180px; line-height: 40px; border-radius: 3px; padding: 0px 10px 0px 30px; background-size: 100%; cursor: pointer; transition: all 0.8s; -webkit-transition: all 0.8s; z-index: 9; box-shadow: 0 14px 28px rgba(0, 0, 0, 0.25), 0 10px 10px rgba(0, 0, 0, 0.1); border-radius: 50px !important; /* width: 175px !important; */ left: 33px; bottom: 37px }.hotline-bar > a{ color: #fff; text-decoration: none; font-size: 16px; font-weight: bold; text-indent: 22px; display: block; letter-spacing: 1px; line-height: 40px; font-family: Arial }.hotline-bar > a:hover,.hotline-bar > a:active{ color: #fff }@-webkit-keyframes phonering-alo-circle-anim {0%{ -webkit-transform: rotate(0) scale(0.5) skew(1deg); -webkit-opacity: 0.1 }30%{ -webkit-transform: rotate(0) scale(0.7) skew(1deg); -webkit-opacity: 0.5 }100%{ -webkit-transform: rotate(0) scale(1) skew(1deg); -webkit-opacity: 0.1 }}@-webkit-keyframes phonering-alo-circle-fill-anim {0%{ -webkit-transform: rotate(0) scale(0.7) skew(1deg); opacity: 0.6 }50%{ -webkit-transform: rotate(0) scale(1) skew(1deg); opacity: 0.6 }100%{ -webkit-transform: rotate(0) scale(0.7) skew(1deg); opacity: 0.6 }}@-webkit-keyframes phonering-alo-circle-img-anim {0%{ -webkit-transform: rotate(0) scale(1) skew(1deg) }10%{ -webkit-transform: rotate(-25deg) scale(1) skew(1deg) }20%{ -webkit-transform: rotate(25deg) scale(1) skew(1deg) } 30%{ -webkit-transform: rotate(-25deg) scale(1) skew(1deg) }40%{ -webkit-transform: rotate(25deg) scale(1) skew(1deg) }50%{ -webkit-transform: rotate(0) scale(1) skew(1deg) }100%{ -webkit-transform: rotate(0) scale(1) skew(1deg) }}@media (max-width: 768px) {.hotline-bar{ display: none }}.label-new.menu-item > a:after{content:"New";}.label-hot.menu-item > a:after{content:"Hot";}.label-sale.menu-item > a:after{content:"Sale";}.label-popular.menu-item > a:after{content:"Popular";}</style><noscript><style id="rocket-lazyload-nojs-css">.rll-youtube-player, [data-lazy-src]{display:none !important;}</style></noscript><script type="rocketlazyloadscript">
/*! loadCSS rel=preload polyfill. [c]2017 Filament Group, Inc. MIT License */
(function(w){"use strict";if(!w.loadCSS){w.loadCSS=function(){}}
var rp=loadCSS.relpreload={};rp.support=(function(){var ret;try{ret=w.document.createElement("link").relList.supports("preload")}catch(e){ret=!1}
return function(){return ret}})();rp.bindMediaToggle=function(link){var finalMedia=link.media||"all";function enableStylesheet(){link.media=finalMedia}
if(link.addEventListener){link.addEventListener("load",enableStylesheet)}else if(link.attachEvent){link.attachEvent("onload",enableStylesheet)}
setTimeout(function(){link.rel="stylesheet";link.media="only x"});setTimeout(enableStylesheet,3000)};rp.poly=function(){if(rp.support()){return}
var links=w.document.getElementsByTagName("link");for(var i=0;i<links.length;i++){var link=links[i];if(link.rel==="preload"&&link.getAttribute("as")==="style"&&!link.getAttribute("data-loadcss")){link.setAttribute("data-loadcss",!0);rp.bindMediaToggle(link)}}};if(!rp.support()){rp.poly();var run=w.setInterval(rp.poly,500);if(w.addEventListener){w.addEventListener("load",function(){rp.poly();w.clearInterval(run)})}else if(w.attachEvent){w.attachEvent("onload",function(){rp.poly();w.clearInterval(run)})}}
if(typeof exports!=="undefined"){exports.loadCSS=loadCSS}
else{w.loadCSS=loadCSS}}(typeof global!=="undefined"?global:this))
</script></head>

<body class="home page-template page-template-page-blank page-template-page-blank-php page page-id-3229 theme-flatsome woocommerce-no-js wp-schema-pro-2.6.5 full-width lightbox nav-dropdown-has-arrow nav-dropdown-has-shadow nav-dropdown-has-border parallax-mobile elementor-default elementor-kit-2282">

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-WCZLXS4"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->

<div id="fb-root"></div>
<script type="rocketlazyloadscript" async defer crossorigin="anonymous" src="https://connect.facebook.net/vi_VN/sdk.js#xfbml=1&version=v11.0&appId=705097193446161&autoLogAppEvents=1" nonce="Kw4gUKGX"></script>
<a class="skip-link screen-reader-text" href="#main">Skip to content</a>

<div id="wrapper">

	
	<header id="header" class="header has-sticky sticky-jump">
		<div class="header-wrapper">
			<div id="masthead" class="header-main ">
      <div class="header-inner flex-row container logo-left medium-logo-center" role="navigation">

          <!-- Logo -->
          <div id="logo" class="flex-col logo">
            <!-- Header logo -->
<a href="https://remcuahn.com/" title="remcuahn.com - Mẫu mành rèm cửa đẹp" rel="home">
    <img width="200" height="101" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20200%20101'%3E%3C/svg%3E" class="header_logo header-logo" alt="remcuahn.com" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/08/logo-300-100.png"/><noscript><img width="200" height="101" src="https://remcuahn.com/wp-content/uploads/2021/08/logo-300-100.png" class="header_logo header-logo" alt="remcuahn.com"/></noscript><img  width="200" height="101" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20200%20101'%3E%3C/svg%3E" class="header-logo-dark" alt="remcuahn.com" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/08/logo-300-100.png"/><noscript><img  width="200" height="101" src="https://remcuahn.com/wp-content/uploads/2021/08/logo-300-100.png" class="header-logo-dark" alt="remcuahn.com"/></noscript></a>
          </div>

          <!-- Mobile Left Elements -->
          <div class="flex-col show-for-medium flex-left">
            <ul class="mobile-nav nav nav-left ">
              <li class="nav-icon has-icon">
  		<a href="#" data-open="#main-menu" data-pos="left" data-bg="main-menu-overlay" data-color="" class="is-small" aria-label="Menu" aria-controls="main-menu" aria-expanded="false">
		
		  <i class="icon-menu" ></i>
		  		</a>
	</li>            </ul>
          </div>

          <!-- Left Elements -->
          <div class="flex-col hide-for-medium flex-left
            flex-grow">
            <ul class="header-nav header-nav-main nav nav-left  nav-uppercase" >
              <li id="menu-item-3248" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home current-menu-item page_item page-item-3229 current_page_item menu-item-3248 active menu-item-design-default"><a href="https://remcuahn.com/" aria-current="page" class="nav-top-link">Trang Chủ</a></li>
<li id="menu-item-90" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-90 menu-item-design-container-width menu-item-has-block has-dropdown"><a href="https://remcuahn.com/rem-cua/" class="nav-top-link">Rèm Cửa<i class="icon-angle-down" ></i></a><div class="sub-menu nav-dropdown"><div class="row row-collapse align-equal"  id="row-1023198132">


	<div id="col-886140252" class="col medium-12 small-12 large-6"  >
				<div class="col-inner text-left" style="background-color:rgb(190, 178, 173);" >
			
			

<div class="row row-collapse align-equal"  id="row-3278956">


	<div id="col-936666844" class="col medium-6 small-12 large-6"  >
				<div class="col-inner"  >
			
			

	<div class="box has-hover   has-hover box-text-bottom" >

		<div class="box-image" >
						<div class="" >
				<img width="544" height="680" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20544%20680'%3E%3C/svg%3E" class="attachment- size-" alt="Rèm vải 2 lớp" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/08/rem-vai-2-lop.jpg 544w, https://remcuahn.com/wp-content/uploads/2021/08/rem-vai-2-lop-510x638.jpg 510w" data-lazy-sizes="(max-width: 544px) 100vw, 544px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/08/rem-vai-2-lop.jpg" /><noscript><img width="544" height="680" src="https://remcuahn.com/wp-content/uploads/2021/08/rem-vai-2-lop.jpg" class="attachment- size-" alt="Rèm vải 2 lớp" srcset="https://remcuahn.com/wp-content/uploads/2021/08/rem-vai-2-lop.jpg 544w, https://remcuahn.com/wp-content/uploads/2021/08/rem-vai-2-lop-510x638.jpg 510w" sizes="(max-width: 544px) 100vw, 544px" /></noscript>											</div>
					</div>

		<div class="box-text text-center" >
			<div class="box-text-inner">
				

	<div id="text-92838658" class="text">
		

<h4>Rèm Vải 2 Lớp</h4>
		
<style>
#text-92838658 {
  color: rgb(255, 255, 255);
}
#text-92838658 > * {
  color: rgb(255, 255, 255);
}
</style>
	</div>
	

			</div>
		</div>
	</div>
	

		</div>
					</div>

	

	<div id="col-816519402" class="col medium-6 small-12 large-6"  >
				<div class="col-inner dark"  >
			
			

<p>MẪU RÈM CỬA</p>
	<div class="ux-menu stack stack-col justify-start ux-menu--divider-solid">
		

	<div class="ux-menu-link flex menu-item label-popular">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-vai/"  >
						<span class="ux-menu-link__text">
				Mẫu Rèm Vải			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item label-new">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-cao-cap/"  >
			<i class="ux-menu-link__icon text-center icon-angle-right" ></i>			<span class="ux-menu-link__text">
				Mẫu Rèm Vải Cao Cấp			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-gia-re/"  >
			<i class="ux-menu-link__icon text-center icon-angle-right" ></i>			<span class="ux-menu-link__text">
				Mẫu Rèm Vải Giá Rẻ			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-hoa-van/"  >
			<i class="ux-menu-link__icon text-center icon-angle-right" ></i>			<span class="ux-menu-link__text">
				Mẫu Rèm Vải Hoa Văn			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item label-popular">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-mot-mau/"  >
			<i class="ux-menu-link__icon text-center icon-angle-right" ></i>			<span class="ux-menu-link__text">
				Mẫu Rèm Vải Một Màu			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-vai/rem-ngan-lanh-dieu-hoa/"  >
						<span class="ux-menu-link__text">
				Mẫu Rèm Ngăn Lạnh Điều Hòa			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item label-new">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/mau-rem-hat-go/"  >
						<span class="ux-menu-link__text">
				Mẫu Rèm Hạt Gỗ			</span>
		</a>
	</div>
	


	</div>
	

		</div>
					</div>

	


<style>
#row-3278956 > .col > .col-inner {
  padding: 10px 10px 10px 10px;
}
</style>
</div>

		</div>
					</div>

	

	<div id="col-220816119" class="col medium-12 small-12 large-6"  >
				<div class="col-inner dark" style="background-color:rgb(190, 178, 173);" >
			
			

<div class="row row-collapse align-equal"  id="row-333707599">


	<div id="col-1908243243" class="col medium-6 small-12 large-6"  >
				<div class="col-inner"  >
			
			

	<div class="box has-hover   has-hover box-text-bottom" >

		<div class="box-image" >
						<div class="" >
				<img width="544" height="680" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20544%20680'%3E%3C/svg%3E" class="attachment- size-" alt="Rèm sáo gỗ" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/08/rem-sao-go.jpg 544w, https://remcuahn.com/wp-content/uploads/2021/08/rem-sao-go-510x638.jpg 510w" data-lazy-sizes="(max-width: 544px) 100vw, 544px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/08/rem-sao-go.jpg" /><noscript><img width="544" height="680" src="https://remcuahn.com/wp-content/uploads/2021/08/rem-sao-go.jpg" class="attachment- size-" alt="Rèm sáo gỗ" srcset="https://remcuahn.com/wp-content/uploads/2021/08/rem-sao-go.jpg 544w, https://remcuahn.com/wp-content/uploads/2021/08/rem-sao-go-510x638.jpg 510w" sizes="(max-width: 544px) 100vw, 544px" /></noscript>											</div>
					</div>

		<div class="box-text text-center" >
			<div class="box-text-inner">
				

	<div id="text-3656318548" class="text">
		

<h4>Rèm Sáo Gỗ</h4>
		
<style>
#text-3656318548 {
  color: rgb(255, 255, 255);
}
#text-3656318548 > * {
  color: rgb(255, 255, 255);
}
</style>
	</div>
	

			</div>
		</div>
	</div>
	

		</div>
					</div>

	

	<div id="col-1654373384" class="col medium-6 small-12 large-6"  >
				<div class="col-inner"  >
			
			

<p>MẪU RÈM CỬA SỔ</p>
	<div class="ux-menu stack stack-col justify-start ux-menu--divider-solid">
		

	<div class="ux-menu-link flex menu-item label-hot">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-roman/"  >
						<span class="ux-menu-link__text">
				Mẫu Rèm Roman			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item label-sale">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-cau-vong/"  >
						<span class="ux-menu-link__text">
				Mẫu Rèm Cầu Vồng			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item label-sale">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-go/"  >
						<span class="ux-menu-link__text">
				Rèm Gỗ - Mành Gỗ			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-cuon/"  >
						<span class="ux-menu-link__text">
				Rèm Cuốn - Màn Cuốn			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-cuon-tranh/"  >
						<span class="ux-menu-link__text">
				Mẫu Rèm Cuốn Tranh			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-la-doc/"  >
						<span class="ux-menu-link__text">
				Mẫu Rèm Lá Dọc			</span>
		</a>
	</div>
	

	<div class="ux-menu-link flex menu-item">
		<a class="ux-menu-link__link flex" href="https://remcuahn.com/danh-muc/rem-sao-nhom/"  >
						<span class="ux-menu-link__text">
				Mẫu Rèm Sáo Nhôm			</span>
		</a>
	</div>
	


	</div>
	

		</div>
					</div>

	


<style>
#row-333707599 > .col > .col-inner {
  padding: 10px 10px 10px 10px;
}
</style>
</div>

		</div>
					</div>

	


<style>
#row-1023198132 > .col > .col-inner {
  padding: 5px 0px 0px 0px;
}
</style>
</div></div></li>
<li id="menu-item-33" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-has-children menu-item-33 menu-item-design-default has-dropdown"><a href="https://remcuahn.com/tu-van-rem-cua/" class="nav-top-link">Tư Vấn Rèm Cửa<i class="icon-angle-down" ></i></a>
<ul class="sub-menu nav-dropdown nav-dropdown-bold">
	<li id="menu-item-41" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-41"><a href="https://remcuahn.com/tu-van-rem-cua/rem-roman/">Rèm Cửa Roman</a></li>
	<li id="menu-item-42" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-42"><a href="https://remcuahn.com/tu-van-rem-cua/man-rem-vai-2-lop/">Màn Rèm Vải 2 Lớp</a></li>
	<li id="menu-item-46" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-46"><a href="https://remcuahn.com/tu-van-rem-cua/rem-vai-mot-mau/">Rèm Vải Một Màu</a></li>
	<li id="menu-item-43" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-43"><a href="https://remcuahn.com/tu-van-rem-cua/rem-cua-cao-cap/">Rèm Cửa Cao Cấp</a></li>
	<li id="menu-item-44" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-44"><a href="https://remcuahn.com/tu-van-rem-cua/rem-dep-gia-re/">Rèm Đẹp Giá Rẻ</a></li>
	<li id="menu-item-47" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-47"><a href="https://remcuahn.com/tu-van-rem-cua/rem-ngan-phong-dieu-hoa/">Rèm Ngăn Phòng Điều Hòa</a></li>
	<li id="menu-item-37" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-37"><a href="https://remcuahn.com/tu-van-rem-cua/rem-cau-vong/">Rèm Cửa Cầu Vồng</a></li>
	<li id="menu-item-39" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-39"><a href="https://remcuahn.com/tu-van-rem-cua/rem-go/">Rèm Sáo Gỗ</a></li>
	<li id="menu-item-38" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-38"><a href="https://remcuahn.com/tu-van-rem-cua/rem-cuon/">Rèm Cửa Cuốn</a></li>
	<li id="menu-item-40" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-40"><a href="https://remcuahn.com/tu-van-rem-cua/rem-la-doc/">Rèm Cửa Lá Dọc</a></li>
	<li id="menu-item-36" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-36"><a href="https://remcuahn.com/tu-van-rem-cua/man-sao-nhom/">Màn Sáo Nhôm</a></li>
	<li id="menu-item-2587" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-2587"><a href="https://remcuahn.com/rem-hat-go-phong-thuy/">Rèm hạt gỗ phong thủy</a></li>
</ul>
</li>
<li id="menu-item-32" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-has-children menu-item-32 menu-item-design-default has-dropdown"><a href="https://remcuahn.com/tin-tuc/" class="nav-top-link">Tin Tức<i class="icon-angle-down" ></i></a>
<ul class="sub-menu nav-dropdown nav-dropdown-bold">
	<li id="menu-item-2086" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-2086"><a href="https://remcuahn.com/mau-rem-cua-so-dep-bao-gia-nam-2020/">Rèm cửa sổ đẹp</a></li>
	<li id="menu-item-2328" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-2328"><a href="https://remcuahn.com/mau-rem-roman-rem-xep-lop/">Mẫu rèm ROMAN</a></li>
	<li id="menu-item-35" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-35"><a href="https://remcuahn.com/tin-tuc/khach-hang/">Khách Hàng</a></li>
	<li id="menu-item-34" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-34"><a href="https://remcuahn.com/tin-tuc/bao-gia/">Báo Giá</a></li>
</ul>
</li>
<li id="menu-item-1080" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1080 menu-item-design-default"><a href="https://remcuahn.com/lien-he/" class="nav-top-link">Liên Hệ</a></li>
            </ul>
          </div>

          <!-- Right Elements -->
          <div class="flex-col hide-for-medium flex-right">
            <ul class="header-nav header-nav-main nav nav-right  nav-uppercase">
              <li class="header-search header-search-dropdown has-icon has-dropdown menu-item-has-children">
	<div class="header-button">	<a href="#" aria-label="Tìm kiếm" class="icon button round is-outline is-small"><i class="icon-search" ></i></a>
	</div>	<ul class="nav-dropdown nav-dropdown-bold">
	 	<li class="header-search-form search-form html relative has-icon">
	<div class="header-search-form-wrapper">
		<div class="searchform-wrapper ux-search-box relative is-normal"><form role="search" method="get" class="searchform" action="https://remcuahn.com/">
	<div class="flex-row relative">
						<div class="flex-col flex-grow">
			<label class="screen-reader-text" for="woocommerce-product-search-field-0">Tìm kiếm:</label>
			<input type="search" id="woocommerce-product-search-field-0" class="search-field mb-0" placeholder="Tìm kiếm&hellip;" value="" name="s" />
			<input type="hidden" name="post_type" value="product" />
					</div>
		<div class="flex-col">
			<button type="submit" value="Tìm kiếm" class="ux-search-submit submit-button secondary button icon mb-0" aria-label="Submit">
				<i class="icon-search" ></i>			</button>
		</div>
	</div>
	<div class="live-search-results text-left z-top"></div>
</form>
</div>	</div>
</li>	</ul>
</li>
<li class="account-item has-icon
    "
>
<div class="header-button">
<a href="https://remcuahn.com/tai-khoan/"
    class="nav-top-link nav-top-not-logged-in icon button round is-outline is-small"
    data-open="#login-form-popup"  >
    <span>
    Đăng nhập      </span>
  
</a>

</div>

</li>
<li class="cart-item has-icon has-dropdown">
<div class="header-button">
<a href="https://remcuahn.com/gio-hang/" title="Giỏ hàng" class="header-cart-link icon button round is-outline is-small">


<span class="header-cart-title">
   Giỏ hàng   /      <span class="cart-price"><span class="woocommerce-Price-amount amount"><bdi>0<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
  </span>

    <i class="icon-shopping-bag"
    data-icon-label="0">
  </i>
  </a>
</div>
 <ul class="nav-dropdown nav-dropdown-bold">
    <li class="html widget_shopping_cart">
      <div class="widget_shopping_cart_content">
        

	<p class="woocommerce-mini-cart__empty-message">Chưa có sản phẩm trong giỏ hàng.</p>


      </div>
    </li>
     </ul>

</li>
            </ul>
          </div>

          <!-- Mobile Right Elements -->
          <div class="flex-col show-for-medium flex-right">
            <ul class="mobile-nav nav nav-right ">
              <li class="cart-item has-icon">

<div class="header-button">      <a href="https://remcuahn.com/gio-hang/" class="header-cart-link off-canvas-toggle nav-top-link icon button round is-outline is-small" data-open="#cart-popup" data-class="off-canvas-cart" title="Giỏ hàng" data-pos="right">
  
    <i class="icon-shopping-bag"
    data-icon-label="0">
  </i>
  </a>
</div>

  <!-- Cart Sidebar Popup -->
  <div id="cart-popup" class="mfp-hide widget_shopping_cart">
  <div class="cart-popup-inner inner-padding">
      <div class="cart-popup-title text-center">
          <h4 class="uppercase">Giỏ hàng</h4>
          <div class="is-divider"></div>
      </div>
      <div class="widget_shopping_cart_content">
          

	<p class="woocommerce-mini-cart__empty-message">Chưa có sản phẩm trong giỏ hàng.</p>


      </div>
             <div class="cart-sidebar-content relative"></div>  </div>
  </div>

</li>
            </ul>
          </div>

      </div>
     
            <div class="container"><div class="top-divider full-width"></div></div>
      </div>
<div class="header-bg-container fill"><div class="header-bg-image fill"></div><div class="header-bg-color fill"></div></div>		</div>
	</header>

	
	<main id="main" class="">


<div id="content" role="main" class="content-area">

		
				<section class="section" id="section_1152209641">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			<div class="section-bg-overlay absolute fill"></div>
			

		</div>

		<div class="section-content relative">
			
  <div class="banner-grid-wrapper">
  <div id="banner-grid-940645310" class="banner-grid row row-grid row-xsmall row-box-shadow-1" data-packery-options="">
                      
<div class="col grid-col small-13 large-8 grid-col-1-2" ><div class="col-inner">

  <div class="banner has-hover bg-zoom" id="banner-1013100804">
          <div class="banner-inner fill">
        <div class="banner-bg fill" >
            <div class="bg fill bg-fill bg-loaded"></div>
                                    
                    </div>
        <div class="banner-layers container">
            <div class="fill banner-link"></div>            
   <div id="text-box-252891205" class="text-box banner-layer x50 md-x50 lg-x10 y95 md-y90 lg-y90 res-text">
                     <div data-animate="fadeInLeft">           <div class="text-box-content text dark">
              
              <div class="text-inner text-center">
                  
	<div id="text-560012658" class="text">
		
<h6 class="uppercase" style="text-align: center;">Rèm Vải</h6>
<h2 style="text-align: center;"><span style="font-size: 85%;">Rèm Vải Đẹp &#8211; Sang Trọng</span></h2>
<p class="lead">Sản phẩm màn rèm vải phổ biến nhất hiện nay &#8211; Giải pháp chống nắng, che phủ tốt nhất cho phòng khách và phòng ngủ.</p>
		
<style>
#text-560012658 {
  color: rgb(255, 255, 255);
}
#text-560012658 > * {
  color: rgb(255, 255, 255);
}
</style>
	</div>
	
              </div>
           </div>
       </div>                     
<style>
#text-box-252891205 .text-box-content {
  border-radius: 70px;
  font-size: 100%;
}
#text-box-252891205 {
  width: 100%;
}
@media (min-width:550px) {
  #text-box-252891205 {
    width: 96%;
  }
}
@media (min-width:850px) {
  #text-box-252891205 {
    width: 74%;
  }
}
</style>
    </div>
 
        </div>
      </div>

            
<style>
#banner-1013100804 {
  padding-top: 500px;
}
#banner-1013100804 .bg.bg-loaded {
  background-image: url(https://remcuahn.com/wp-content/uploads/2021/08/mau-rem-cua.jpg);
}
#banner-1013100804 .bg {
  background-position: 32% 46%;
}
</style>
  </div>


</div></div>
<div class="col grid-col small-13 large-4 grid-col-2-3" ><div class="col-inner">

  <div class="banner has-hover bg-zoom" id="banner-913464261">
          <div class="banner-inner fill">
        <div class="banner-bg fill" >
            <div class="bg fill bg-fill bg-loaded"></div>
                        <div class="overlay"></div>            
                    </div>
        <div class="banner-layers container">
            <div class="fill banner-link"></div>            
   <div id="text-box-1038614507" class="text-box banner-layer x50 md-x50 lg-x50 y65 md-y65 lg-y50 res-text">
                                <div class="text-box-content text dark">
              
              <div class="text-inner text-center">
                  
<h6 class="uppercase" style="text-align: center;"><span style="font-size: 100%;">RÈM GỖ</span></h6>
<h2 style="text-align: center;"><span style="font-size: 80%;">Rèm Cửa Sáo Gỗ</span></h2>
              </div>
           </div>
                            
<style>
#text-box-1038614507 {
  width: 100%;
}
#text-box-1038614507 .text-box-content {
  font-size: 110%;
}
@media (min-width:550px) {
  #text-box-1038614507 {
    width: 100%;
  }
}
@media (min-width:850px) {
  #text-box-1038614507 {
    width: 75%;
  }
}
</style>
    </div>
 
        </div>
      </div>

            
<style>
#banner-913464261 {
  padding-top: 500px;
}
#banner-913464261 .bg.bg-loaded {
  background-image: url(https://remcuahn.com/wp-content/uploads/2021/08/rem-go.jpg);
}
#banner-913464261 .overlay {
  background-color: rgba(0, 0, 0, 0.16);
}
#banner-913464261 .bg {
  background-position: 47% 55%;
}
</style>
  </div>


</div></div>
<div class="col grid-col small-15 large-4 grid-col-1-2" ><div class="col-inner">

  <div class="banner has-hover bg-zoom" id="banner-768658530">
          <div class="banner-inner fill">
        <div class="banner-bg fill" >
            <div class="bg fill bg-fill bg-loaded"></div>
                                    
                    </div>
        <div class="banner-layers container">
            <div class="fill banner-link"></div>            
   <div id="text-box-1196491035" class="text-box banner-layer x50 md-x50 lg-x50 y85 md-y85 lg-y85 res-text">
                     <div data-animate="fadeInLeft">           <div class="text-box-content text ">
              
              <div class="text-inner text-center">
                  
	<div id="text-3611721447" class="text">
		
<h6 class="uppercase" style="text-align: center;"><span style="font-size: 100%;">Rèm Cầu Vồng</span></h6>
<h2 style="text-align: center;"><span style="font-size: 80%;">Mẫu Rèm Cầu Vồng</span></h2>
		
<style>
#text-3611721447 {
  color: rgb(255, 255, 255);
}
#text-3611721447 > * {
  color: rgb(255, 255, 255);
}
</style>
	</div>
	
              </div>
           </div>
       </div>                     
<style>
#text-box-1196491035 .text-box-content {
  border-radius: 30px;
  font-size: 110%;
}
#text-box-1196491035 {
  width: 84%;
}
@media (min-width:550px) {
  #text-box-1196491035 {
    width: 85%;
  }
}
@media (min-width:850px) {
  #text-box-1196491035 {
    width: 75%;
  }
}
</style>
    </div>
 
        </div>
      </div>

            
<style>
#banner-768658530 {
  padding-top: 500px;
}
#banner-768658530 .bg.bg-loaded {
  background-image: url(https://remcuahn.com/wp-content/uploads/2021/08/rem-cau-vong.jpg);
}
#banner-768658530 .bg {
  background-position: 48% 36%;
}
</style>
  </div>


</div></div>
<div class="col grid-col small-13 large-4 grid-col-1-2" ><div class="col-inner">

  <div class="banner has-hover bg-zoom" id="banner-355338921">
          <div class="banner-inner fill">
        <div class="banner-bg fill" >
            <div class="bg fill bg-fill bg-loaded"></div>
                                    
                    </div>
        <div class="banner-layers container">
            <div class="fill banner-link"></div>            
   <div id="text-box-549766460" class="text-box banner-layer x50 md-x50 lg-x50 y90 md-y85 lg-y85 res-text">
                                <div class="text-box-content text dark">
              
              <div class="text-inner text-center">
                  
	<div id="text-2524116730" class="text">
		
<h6 class="uppercase" style="text-align: center;"><span style="font-size: 100%;">RÈM ROMAN</span></h6>
<h2 style="text-align: center;"><span style="font-size: 80%;">Mẫu Rèm ROMAN</span></h2>
		
<style>
#text-2524116730 {
  text-align: center;
}
</style>
	</div>
	
              </div>
           </div>
                            
<style>
#text-box-549766460 .text-box-content {
  border-radius: 30px;
  font-size: 100%;
}
#text-box-549766460 {
  width: 73%;
}
@media (min-width:550px) {
  #text-box-549766460 {
    width: 77%;
  }
}
@media (min-width:850px) {
  #text-box-549766460 {
    width: 65%;
  }
}
</style>
    </div>
 
        </div>
      </div>

            
<style>
#banner-355338921 {
  padding-top: 500px;
}
#banner-355338921 .bg.bg-loaded {
  background-image: url(https://remcuahn.com/wp-content/uploads/2021/08/rem-roman.jpg);
}
</style>
  </div>


</div></div>
<div class="col grid-col small-15 large-4 grid-col-1-3" ><div class="col-inner">

  <div class="banner has-hover bg-zoom" id="banner-607531108">
          <div class="banner-inner fill">
        <div class="banner-bg fill" >
            <div class="bg fill bg-fill bg-loaded"></div>
                        <div class="overlay"></div>            
                    </div>
        <div class="banner-layers container">
            <div class="fill banner-link"></div>            
   <div id="text-box-439842216" class="text-box banner-layer x50 md-x50 lg-x50 y85 md-y80 lg-y75 res-text">
                                <div class="text-box-content text dark">
              
              <div class="text-inner text-center">
                  
	<div id="text-3959023605" class="text">
		
<h6 class="uppercase" style="text-align: center;"><span style="font-size: 100%;">RÈM CUỐN</span></h6>
<h2 style="text-align: center;"><span style="font-size: 80%;">Rèm cuốn chống nắng</span></h2>
		
<style>
#text-3959023605 {
  text-align: center;
}
</style>
	</div>
	
              </div>
           </div>
                            
<style>
#text-box-439842216 {
  width: 100%;
}
#text-box-439842216 .text-box-content {
  font-size: 110%;
}
@media (min-width:550px) {
  #text-box-439842216 {
    width: 99%;
  }
}
@media (min-width:850px) {
  #text-box-439842216 {
    width: 75%;
  }
}
</style>
    </div>
 
        </div>
      </div>

            
<style>
#banner-607531108 {
  padding-top: 500px;
}
#banner-607531108 .bg.bg-loaded {
  background-image: url(https://remcuahn.com/wp-content/uploads/2021/08/rem-cuon.jpg);
}
#banner-607531108 .overlay {
  background-color: rgba(0, 0, 0, 0.09);
}
</style>
  </div>


</div></div>
            </div>
    <style>
    #banner-grid-940645310 .grid-col-1{height: 666px}
    #banner-grid-940645310 .grid-col-1-2{height: 333px}
    #banner-grid-940645310 .grid-col-1-3{height:222px}
    #banner-grid-940645310 .grid-col-2-3{height: 444px}
    #banner-grid-940645310 .grid-col-1-4{height: 166.5px}
    #banner-grid-940645310 .grid-col-3-4{height: 499.5px}


    
    

  </style>
    </div>
  
		</div>

		
<style>
#section_1152209641 {
  padding-top: 15px;
  padding-bottom: 15px;
  background-color: rgb(255, 255, 255);
}
#section_1152209641 .section-bg-overlay {
  background-color: rgba(255, 255, 255, 0.62);
}
</style>
	</section>
	
	<section class="section" id="section_1906771994">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			
<div class="container section-title-container" ><h1 class="section-title section-title-bold-center"><b></b><span class="section-title-main" style="font-size:80%;">Rèm cửa đi, cửa sổ phòng khách, phòng ngủ đẹp, giá rẻ</span><b></b></h1></div>
		</div>

		
<style>
#section_1906771994 {
  padding-top: 0px;
  padding-bottom: 0px;
}
</style>
	</section>
	
	<section class="section" id="section_1307511545">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			
<div class="row"  id="row-1068431744">

	<div id="col-916802717" class="col medium-4 small-12 large-3"  >
				<div class="col-inner"  >
			
			
<div class="row row-box-shadow-2"  id="row-2126186144">

	<div id="col-1376972671" class="col small-12 large-12"  >
				<div class="col-inner text-center"  >
			
			
<ul class="sidebar-wrapper ul-reset"><li id="nav_menu-2" class="widget widget_nav_menu"><h2 class="widgettitle">Rèm Vải</h2>
<div class="menu-san-pham-rem-vai-container"><ul id="menu-san-pham-rem-vai" class="menu"><li id="menu-item-3242" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-3242"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-cao-cap/">Mẫu Rèm Vải Cao Cấp</a></li>
<li id="menu-item-3245" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-3245"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-mot-mau/">Mẫu Rèm Vải Một Màu</a></li>
<li id="menu-item-3244" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-3244"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-hoa-van/">Mẫu Rèm Vải Hoa Văn</a></li>
<li id="menu-item-3243" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-3243"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-gia-re/">Mẫu Rèm Vải Giá Rẻ</a></li>
<li id="menu-item-3246" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-3246"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-ngan-lanh-dieu-hoa/">Rèm Ngăn Lạnh Điều Hòa</a></li>
<li id="menu-item-3253" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-3253"><a href="https://remcuahn.com/danh-muc/rem-roman/">Mẫu Rèm Roman</a></li>
</ul></div></li></ul>
		</div>
				
<style>
#col-1376972671 > .col-inner {
  padding: 0px 0px 0px 0px;
  margin: 0px 0px -13px 0px;
}
</style>
	</div>

	

<style>
#row-2126186144 > .col > .col-inner {
  padding: 4px 0px 10px 0px;
}
</style>
</div>
<div class="row"  id="row-1123943397">

	<div id="col-2145844297" class="col small-12 large-12"  >
				<div class="col-inner"  >
			
			
	<div class="img has-hover x md-x lg-x y md-y lg-y" id="image_1453606165">
								<div class="img-inner dark" >
			<img width="450" height="199" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20450%20199'%3E%3C/svg%3E" class="attachment-large size-large" alt="Hotline" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/08/hotline.gif" /><noscript><img width="450" height="199" src="https://remcuahn.com/wp-content/uploads/2021/08/hotline.gif" class="attachment-large size-large" alt="Hotline" /></noscript>						
					</div>
								
<style>
#image_1453606165 {
  width: 100%;
}
</style>
	</div>
	
		</div>
				
<style>
#col-2145844297 > .col-inner {
  margin: 0px 0px -6px 0px;
}
</style>
	</div>

	
</div>
<div class="row"  id="row-672551886">

	<div id="col-495138866" class="col small-12 large-12"  >
				<div class="col-inner"  >
			
			

  <div class="banner has-hover bg-zoom" id="banner-246858949">
          <div class="banner-inner fill">
        <div class="banner-bg fill" >
            <div class="bg fill bg-fill bg-loaded"></div>
                        <div class="overlay"></div>            
                    </div>
        <div class="banner-layers container">
            <div class="fill banner-link"></div>            
   <div id="text-box-1956886298" class="text-box banner-layer x50 md-x50 lg-x50 y90 md-y90 lg-y90 res-text">
                                <div class="text-box-content text dark text-shadow-5">
              
              <div class="text-inner text-center">
                  
	<div id="text-3235207098" class="text">
		
<h4 class="uppercase">Mùa hè 2021</h4>
<h3 class="uppercase"><strong>Chương trình khuyến Mãi</strong></h3>
		
<style>
#text-3235207098 {
  color: rgb(255, 255, 255);
}
#text-3235207098 > * {
  color: rgb(255, 255, 255);
}
</style>
	</div>
	
              </div>
           </div>
                            
<style>
#text-box-1956886298 .text-box-content {
  background-color: rgba(255, 0, 0, 0.791);
  font-size: 100%;
}
#text-box-1956886298 {
  width: 100%;
}
</style>
    </div>
 
   <div id="text-box-1277650234" class="text-box banner-layer text-box-circle x100 md-x100 lg-x100 y5 md-y5 lg-y5 res-text">
                                <div class="text-box-content text dark">
              
              <div class="text-inner text-center">
                  
<p><span style="font-size: 250%;"><strong>SALE</strong></span></p>
              </div>
           </div>
                            
<style>
#text-box-1277650234 {
  margin: 0px -5px 0px 0px;
  width: 26%;
}
#text-box-1277650234 .text-box-content {
  background-color: rgba(255, 0, 0, 0.791);
  font-size: 100%;
}
</style>
    </div>
 
        </div>
      </div>

            
<style>
#banner-246858949 {
  padding-top: 316px;
}
#banner-246858949 .bg.bg-loaded {
  background-image: url(https://remcuahn.com/wp-content/uploads/2021/08/rem-vai-can-nang.jpg);
}
#banner-246858949 .overlay {
  background-color: rgba(0, 0, 0, 0.2);
}
#banner-246858949 .bg {
  background-position: 10% 42%;
}
</style>
  </div>


		</div>
					</div>

	
</div>
		</div>
					</div>

	

	<div id="col-1666058705" class="col medium-8 small-12 large-9"  >
				<div class="col-inner"  >
			
			

  
    <div class="row  equalize-box large-columns-3 medium-columns- small-columns-2 row-small slider row-slider slider-nav-reveal slider-nav-push"  data-flickity-options='{"imagesLoaded": true, "groupCells": "100%", "dragThreshold" : 5, "cellAlign": "left","wrapAround": true,"prevNextButtons": true,"percentPosition": true,"pageDots": false, "rightToLeft": false, "autoPlay" : false}'>

  	
	     
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-30%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/manh-dung-klimt-elise-han-quoc/" aria-label="Mành đứng KLIMT, ELISE Hàn Quốc">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành dọc Hàn Quốc" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/12/manh-doc-han-quoc-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/12/manh-doc-han-quoc-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành dọc Hàn Quốc" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/manh-dung-klimt-elise-han-quoc/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Mành đứng KLIMT, ELISE Hàn Quốc</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>2.300.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>1.610.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cua-2-lop-rv568-phong-khach/" aria-label="Rèm cửa 2 lớp RV568 phòng khách">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa 2 lớp TN568 phòng khách chung cư" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cua-2-lop-phong-khach-TN568-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cua-2-lop-phong-khach-TN568-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa 2 lớp TN568 phòng khách chung cư" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Cao Cấp		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cua-2-lop-rv568-phong-khach/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cửa 2 lớp RV568 phòng khách</a></p></div><div class="price-wrapper"><div class="star-rating" role="img" aria-label="Được xếp hạng 5.00 5 sao"><span style="width:100%">Được xếp hạng <strong class="rating">5.00</strong> 5 sao</span></div>
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>1.100.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-17%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-vai-ni-van-tn950-phong-ngu/" aria-label="Rèm vải nỉ vân TN950 phòng ngủ">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải nỉ vân RV950-9" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-vai-ni-van-rv-950-9-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-vai-ni-van-rv-950-9-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải nỉ vân RV950-9" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Một Màu		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-vai-ni-van-tn950-phong-ngu/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm vải nỉ vân TN950 phòng ngủ</a></p></div><div class="price-wrapper"><div class="star-rating" role="img" aria-label="Được xếp hạng 5.00 5 sao"><span style="width:100%">Được xếp hạng <strong class="rating">5.00</strong> 5 sao</span></div>
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>600.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>500.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-ngan-phong-dieu-hoa-tn51/" aria-label="Rèm ngăn phòng điều hòa TN51">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm ngăn phòng điều hòa TN51" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-ngan-lanh-dieu-hoa-tn51-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-ngan-lanh-dieu-hoa-tn51-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm ngăn phòng điều hòa TN51" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Rèm Ngăn Lạnh Điều Hòa		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-ngan-phong-dieu-hoa-tn51/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm ngăn phòng điều hòa TN51</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>750.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-2-lop-tn568-dep-gia-re/" aria-label="Rèm 2 lớp TN568 đẹp giá rẻ">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải 2 lớp TN568 đẹp giá rẻ" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-vai-2-lop-tn568-phong-ngu-dep-gia-re-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-vai-2-lop-tn568-phong-ngu-dep-gia-re-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải 2 lớp TN568 đẹp giá rẻ" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Một Màu		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-2-lop-tn568-dep-gia-re/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm 2 lớp TN568 đẹp giá rẻ</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>1.000.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-vai-dep-tn892-16-can-nang/" aria-label="Rèm vải đẹp TN892-16 cản nắng">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải đẹp RV892-16 cản nắng" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-vai-dep-rv892-16-can-nang-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-vai-dep-rv892-16-can-nang-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải đẹp RV892-16 cản nắng" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Một Màu		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-vai-dep-tn892-16-can-nang/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm vải đẹp TN892-16 cản nắng</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>650.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cua-2-lop-rv484-6-chong-nang/" aria-label="Rèm cửa 2 lớp RV484-6 chống nắng">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa 2 lớp RV484-6 chống nắng" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cua-2-lop-dep-chong-nang-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cua-2-lop-dep-chong-nang-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa 2 lớp RV484-6 chống nắng" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Một Màu		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cua-2-lop-rv484-6-chong-nang/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cửa 2 lớp RV484-6 chống nắng</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>1.050.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cua-2-lop-tn484-6-gia-dinh/" aria-label="Rèm cửa 2 lớp TN484-6 gia đình">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa đẹp 2 lớp phòng khách gia đình" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cua-2-lop-phong-khach-gia-dinh-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cua-2-lop-phong-khach-gia-dinh-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa đẹp 2 lớp phòng khách gia đình" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Một Màu		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cua-2-lop-tn484-6-gia-dinh/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cửa 2 lớp TN484-6 gia đình</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>950.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cua-vai-han-quoc-dep-gia-re-s-03/" aria-label="Rèm cửa vải Hàn Quốc đẹp giá rẻ S 03">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa vải Hàn Quốc đẹp giá rẻ cho phòng ngủ" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-han-quoc-2-lop-judith-s-03-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-han-quoc-2-lop-judith-s-03-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa vải Hàn Quốc đẹp giá rẻ cho phòng ngủ" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Cao Cấp		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cua-vai-han-quoc-dep-gia-re-s-03/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cửa vải Hàn Quốc đẹp giá rẻ S 03</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>700.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cua-nhat-tn910-phong-tre-em/" aria-label="Rèm cửa Nhật TN910 phòng trẻ em">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa vải Nhật Bản TN910" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/07/rem-cua-nhat-t910-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/07/rem-cua-nhat-t910-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa vải Nhật Bản TN910" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Cao Cấp		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cua-nhat-tn910-phong-tre-em/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cửa Nhật TN910 phòng trẻ em</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>650.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/man-vai-nhat-harmony-tn805-dep/" aria-label="Màn vải Nhật Harmony TN805 đẹp">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải nhật Harmony TN805" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-cua-nhat-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-cua-nhat-340x408.jpg 340w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-cua-nhat-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-cua-nhat-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải nhật Harmony TN805" srcset="https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-cua-nhat-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-cua-nhat-340x408.jpg 340w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Cao Cấp		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/man-vai-nhat-harmony-tn805-dep/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Màn vải Nhật Harmony TN805 đẹp</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>650.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-10%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cua-chong-nang-phong-khach-rv-888-14/" aria-label="Rèm cửa chống nắng phòng khách RV888-14">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải chống nắng cách nhiệt RV888-14" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-chong-nang-cach-nhiet-rv888-14-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/07/rem-vai-chong-nang-cach-nhiet-rv888-14-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải chống nắng cách nhiệt RV888-14" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Một Màu		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cua-chong-nang-phong-khach-rv-888-14/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cửa chống nắng phòng khách RV888-14</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>1.450.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>1.300.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            	        </div>

  
    <div class="row  equalize-box large-columns-3 medium-columns- small-columns-2 row-small slider row-slider slider-nav-reveal slider-nav-push"  data-flickity-options='{"imagesLoaded": true, "groupCells": "100%", "dragThreshold" : 5, "cellAlign": "left","wrapAround": true,"prevNextButtons": true,"percentPosition": true,"pageDots": false, "rightToLeft": false, "autoPlay" : false}'>

  	
	     
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cua-so-rm659-5-phong-ngu-dep/" aria-label="Rèm cửa sổ RM659-5 phòng ngủ đẹp">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa sổ phòng ngủ" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/11/rem-cua-so-roman-phong-ngu-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/11/rem-cua-so-roman-phong-ngu-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/11/rem-cua-so-roman-phong-ngu-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/11/rem-cua-so-roman-phong-ngu-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa sổ phòng ngủ" srcset="https://remcuahn.com/wp-content/uploads/2020/11/rem-cua-so-roman-phong-ngu-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/11/rem-cua-so-roman-phong-ngu-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Roman		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cua-so-rm659-5-phong-ngu-dep/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cửa sổ RM659-5 phòng ngủ đẹp</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>600.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cua-roman-chong-nang-rm886/" aria-label="Rèm cửa roman chống nắng RM886">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa ROMAN chống nắng RM886" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/roman-xep-lop-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/roman-xep-lop-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa ROMAN chống nắng RM886" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Roman		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cua-roman-chong-nang-rm886/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cửa roman chống nắng RM886</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>850.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-roman-rm484-phong-ngu/" aria-label="Rèm roman RM484 phòng ngủ">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm roman kẹp 2 lớp RM484-6 cửa sổ phòng ngủ" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-roman-2-lop-dep-cua-so-phong-ngu-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-roman-2-lop-dep-cua-so-phong-ngu-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm roman kẹp 2 lớp RM484-6 cửa sổ phòng ngủ" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Roman		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-roman-rm484-phong-ngu/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm roman RM484 phòng ngủ</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>650.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/man-roman-2-lop-dep-tn-886/" aria-label="Màn roman 2 lớp đẹp TN-886">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Màn roman 2 lớp TN-886" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/06/romance-2-lop-thanh-nhan-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/romance-2-lop-thanh-nhan-340x408.jpg 340w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/06/romance-2-lop-thanh-nhan-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/06/romance-2-lop-thanh-nhan-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Màn roman 2 lớp TN-886" srcset="https://remcuahn.com/wp-content/uploads/2020/06/romance-2-lop-thanh-nhan-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/romance-2-lop-thanh-nhan-340x408.jpg 340w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Roman		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/man-roman-2-lop-dep-tn-886/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Màn roman 2 lớp đẹp TN-886</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>850.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-7%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-roman-1-lop-rm-23a-11/" aria-label="Rèm roman 1 lớp RM-23A-11">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm roman 1 lớp RM-23A-11" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/09/rem-roman-1-lop-rm-23a-11-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/09/rem-roman-1-lop-rm-23a-11-275x330.jpg 275w, https://remcuahn.com/wp-content/uploads/2019/09/rem-roman-1-lop-rm-23a-11-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/09/rem-roman-1-lop-rm-23a-11-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/09/rem-roman-1-lop-rm-23a-11-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm roman 1 lớp RM-23A-11" srcset="https://remcuahn.com/wp-content/uploads/2019/09/rem-roman-1-lop-rm-23a-11-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/09/rem-roman-1-lop-rm-23a-11-275x330.jpg 275w, https://remcuahn.com/wp-content/uploads/2019/09/rem-roman-1-lop-rm-23a-11-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Roman		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-roman-1-lop-rm-23a-11/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm roman 1 lớp RM-23A-11</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>450.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>420.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-xep-lop-rxl-484-18/" aria-label="Rèm xếp lớp RXL-484-18">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm xếp lớp rxl-484-18" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-xep-lop-rxl-484-18-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-xep-lop-rxl-484-18-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm xếp lớp rxl-484-18" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Roman		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-xep-lop-rxl-484-18/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm xếp lớp RXL-484-18</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>600.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-xep-lop-rxl-484-5/" aria-label="Rèm xếp lớp RXL-484-5">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm xếp lớp RXL-484-5" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-xep-lop-rxl-484-5-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-xep-lop-rxl-484-5-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm xếp lớp RXL-484-5" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Roman		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-xep-lop-rxl-484-5/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm xếp lớp RXL-484-5</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>600.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-21%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-roman-floral-fl-821/" aria-label="Rèm roman FLORAL FL-821">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm roman FLORAL FL-821 Hàn Quốc" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-roman-fl-821-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-roman-fl-821-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm roman FLORAL FL-821 Hàn Quốc" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Roman		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-roman-floral-fl-821/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm roman FLORAL FL-821</a></p></div><div class="price-wrapper"><div class="star-rating" role="img" aria-label="Được xếp hạng 5.00 5 sao"><span style="width:100%">Được xếp hạng <strong class="rating">5.00</strong> 5 sao</span></div>
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>960.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>760.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            	        </div>
		</div>
					</div>

	
</div>
		</div>

		
<style>
#section_1307511545 {
  padding-top: 0px;
  padding-bottom: 0px;
}
</style>
	</section>
	
	<section class="section" id="section_795642281">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			
<div class="container section-title-container" ><h2 class="section-title section-title-bold-center"><b></b><span class="section-title-main" style="font-size:90%;">RÈM CẦU VỒNG HÀN QUỐC</span><b></b></h2></div>

  
    <div class="row  equalize-box large-columns-4 medium-columns-3 small-columns-2 row-small slider row-slider slider-nav-reveal slider-nav-push"  data-flickity-options='{"imagesLoaded": true, "groupCells": "100%", "dragThreshold" : 5, "cellAlign": "left","wrapAround": true,"prevNextButtons": true,"percentPosition": true,"pageDots": false, "rightToLeft": false, "autoPlay" : false}'>

  	
	     
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-20%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cau-vong-victoria-vt-473/" aria-label="Rèm cầu vồng Victoria VT-473">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Victoria VT-473 Hàn Quốc" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-victoria-vt-473-1-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-victoria-vt-473-1-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-victoria-vt-473-1-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-victoria-vt-473-1-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Victoria VT-473 Hàn Quốc" srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-victoria-vt-473-1-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-victoria-vt-473-1-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cau-vong-victoria-vt-473/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cầu vồng Victoria VT-473</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>1.190.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>950.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-23%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cau-vong-claudia-cl-141/" aria-label="Rèm cầu vồng Claudia CL-141">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Claudia CL-141 Hàn Quốc" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-claudia-cl-141-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-claudia-cl-141-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-claudia-cl-141-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-claudia-cl-141-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Claudia CL-141 Hàn Quốc" srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-claudia-cl-141-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-claudia-cl-141-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cau-vong-claudia-cl-141/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cầu vồng Claudia CL-141</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>1.230.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>950.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-20%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cau-vong-oscar-os-635/" aria-label="Rèm cầu vồng OSCAR OS-635">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Oscar OS-635" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-os-635-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-os-635-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-os-635-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-os-635-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Oscar OS-635" srcset="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-os-635-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-os-635-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cau-vong-oscar-os-635/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cầu vồng OSCAR OS-635</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>1.180.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>940.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-20%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cuon-cau-vong-nice-nc-164/" aria-label="Rèm cuốn cầu vồng NICE NC-164">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn cầu vồng NICE NC-164" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-nice-nc-164-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-nice-nc-164-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn cầu vồng NICE NC-164" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cuon-cau-vong-nice-nc-164/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cuốn cầu vồng NICE NC-164</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>1.050.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>840.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-21%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cau-vong-alice-ae-525/" aria-label="Rèm cầu vồng ALICE AE-525">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Alice AE-525" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-alice-ae-525-2018-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-alice-ae-525-2018-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Alice AE-525" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cau-vong-alice-ae-525/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cầu vồng ALICE AE-525</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>780.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>620.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-20%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cau-vong-lauren-au-753/" aria-label="Rèm cầu vồng Lauren AU-753">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng LaurenAU-753" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-lauren-au-753-2018-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-lauren-au-753-2018-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng LaurenAU-753" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cau-vong-lauren-au-753/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cầu vồng Lauren AU-753</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>750.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>600.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-17%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cau-vong-cube-line-cl-313/" aria-label="Rèm cầu vồng Cube Line CL-313">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Cube Line CL-313" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-han-quoc-dep-hn-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-han-quoc-dep-hn-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-han-quoc-dep-hn-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-han-quoc-dep-hn-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Cube Line CL-313" srcset="https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-han-quoc-dep-hn-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/08/rem-cau-vong-han-quoc-dep-hn-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cau-vong-cube-line-cl-313/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cầu vồng Cube Line CL-313</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>1.210.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>1.000.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-25%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/manh-cau-vong-nicole/" aria-label="Mành cầu vồng NICOLE">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Nicole CE-154" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/06/rem-cau-vong-nicole-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/rem-cau-vong-nicole-340x408.jpg 340w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/06/rem-cau-vong-nicole-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/06/rem-cau-vong-nicole-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng Nicole CE-154" srcset="https://remcuahn.com/wp-content/uploads/2020/06/rem-cau-vong-nicole-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/rem-cau-vong-nicole-340x408.jpg 340w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/manh-cau-vong-nicole/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Mành cầu vồng NICOLE</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>860.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>645.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            	        </div>
		</div>

		
<style>
#section_795642281 {
  padding-top: 10px;
  padding-bottom: 10px;
}
</style>
	</section>
	
	<section class="section" id="section_560375078">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			
<div class="container section-title-container" ><h2 class="section-title section-title-bold-center"><b></b><span class="section-title-main" style="font-size:90%;">MÀNH RÈM SÁO GỖ</span><b></b></h2></div>

  
    <div class="row  equalize-box large-columns-4 medium-columns-3 small-columns-2 row-small slider row-slider slider-nav-reveal slider-nav-push"  data-flickity-options='{"imagesLoaded": true, "groupCells": "100%", "dragThreshold" : 5, "cellAlign": "left","wrapAround": true,"prevNextButtons": true,"percentPosition": true,"pageDots": false, "rightToLeft": false, "autoPlay" : false}'>

  	
	     
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-sao-cua-so-go-tuong-msj-194/" aria-label="Rèm sáo cửa sổ gỗ Tượng msj 194">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm gỗ Tượng mã MSJ 194" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/07/rem-go-tuong-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2021/07/rem-go-tuong-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm gỗ Tượng mã MSJ 194" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-sao-cua-so-go-tuong-msj-194/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm sáo cửa sổ gỗ Tượng msj 194</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>1.001.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/man-sao-go-tuong-cao-cap-msj-191/" aria-label="Màn sáo gỗ Tượng cao cấp MSJ 191">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Màn sáo gỗ MSJ 191" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/07/man-sao-go-msj-191-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2021/07/man-sao-go-msj-191-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Màn sáo gỗ MSJ 191" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/man-sao-go-tuong-cao-cap-msj-191/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Màn sáo gỗ Tượng cao cấp MSJ 191</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>1.001.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-go-cao-cap-ma-rg-061/" aria-label="Rèm gỗ cao cấp mã RG - 061">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm gỗ cao cấp RG-061" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/07/rem-go-cao-cap-rg-061-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2021/07/rem-go-cao-cap-rg-061-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm gỗ cao cấp RG-061" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-go-cao-cap-ma-rg-061/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm gỗ cao cấp mã RG &#8211; 061</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>937.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/manh-go-bach-msj-703/" aria-label="Mành gỗ Bách MSJ-703">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm sáo gỗ Bách tự nhiên" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/06/manh-go-bach-msj-703-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/06/manh-go-bach-msj-703-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm sáo gỗ Bách tự nhiên" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/manh-go-bach-msj-703/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Mành gỗ Bách MSJ-703</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>710.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-nhua-gia-go-msj-507/" aria-label="Rèm nhựa giả gỗ MSJ-507">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm nhựa giả gỗ MSJ-507" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/06/mau-rem-nhua-dep-msj-507-1-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/06/mau-rem-nhua-dep-msj-507-1-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm nhựa giả gỗ MSJ-507" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-nhua-gia-go-msj-507/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm nhựa giả gỗ MSJ-507</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>580.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-go-msj-303-mau-vang/" aria-label="Rèm gỗ MSJ-303 màu vàng">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm sáo gỗ MSJ-303 tự nhiên" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/08/rem-sao-go-msj-303-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/08/rem-sao-go-msj-303-275x330.jpg 275w, https://remcuahn.com/wp-content/uploads/2019/08/rem-sao-go-msj-303-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-sao-go-msj-303-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-sao-go-msj-303-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm sáo gỗ MSJ-303 tự nhiên" srcset="https://remcuahn.com/wp-content/uploads/2019/08/rem-sao-go-msj-303-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/08/rem-sao-go-msj-303-275x330.jpg 275w, https://remcuahn.com/wp-content/uploads/2019/08/rem-sao-go-msj-303-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-go-msj-303-mau-vang/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm gỗ MSJ-303 màu vàng</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>550.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-23%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-nhua-msj-503/" aria-label="Rèm nhựa MSJ-503">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm nhựa MSJ-503" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-nhua-msj-503-1-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-nhua-msj-503-1-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-nhua-msj-503-1-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-nhua-msj-503-1-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm nhựa MSJ-503" srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-nhua-msj-503-1-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-nhua-msj-503-1-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-nhua-msj-503/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm nhựa MSJ-503</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>710.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>550.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/manh-go-msj-303-tu-nhien/" aria-label="Mành sáo gỗ MSJ-303 tự nhiên">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành gỗ MSJ-303 tự nhiên" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-go-msj-303-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-go-msj-303-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-go-msj-303-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-go-msj-303-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành gỗ MSJ-303 tự nhiên" srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-go-msj-303-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-go-msj-303-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/manh-go-msj-303-tu-nhien/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Mành sáo gỗ MSJ-303 tự nhiên</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>690.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            	        </div>
		</div>

		
<style>
#section_560375078 {
  padding-top: 10px;
  padding-bottom: 10px;
}
</style>
	</section>
	
	<section class="section" id="section_1007371646">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			
<div class="container section-title-container" ><h2 class="section-title section-title-bold-center"><b></b><span class="section-title-main" style="font-size:90%;">RÈM CUỐN CHỐNG NẮNG</span><b></b></h2></div>

  
    <div class="row  equalize-box large-columns-4 medium-columns-3 small-columns-2 row-small slider row-slider slider-nav-reveal slider-nav-push"  data-flickity-options='{"imagesLoaded": true, "groupCells": "100%", "dragThreshold" : 5, "cellAlign": "left","wrapAround": true,"prevNextButtons": true,"percentPosition": true,"pageDots": false, "rightToLeft": false, "autoPlay" : false}'>

  	
	     
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-19%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/manh-cuon-chong-nang-han-quoc/" aria-label="Mành cuốn chống nắng Hàn Quốc">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành cuốn Thanh Nhàn" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-340x408.jpg 340w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành cuốn Thanh Nhàn" srcset="https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-340x408.jpg 340w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/manh-cuon-chong-nang-han-quoc/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Mành cuốn chống nắng Hàn Quốc</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>740.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>600.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-21%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cuon-hoa-van-fo-891-korea/" aria-label="Rèm cuốn hoa văn FO-891 Korea">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn hoa văn FO-891 KOREA" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cuon-hoa-van-fo-891-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cuon-hoa-van-fo-891-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn hoa văn FO-891 KOREA" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cuon-hoa-van-fo-891-korea/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cuốn hoa văn FO-891 Korea</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>780.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>620.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-21%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cuon-hoa-van-fo-893-korea/" aria-label="Rèm cuốn hoa văn FO-893 Korea">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn hoa văn FO-893 Hàn Quốc" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cuon-hoa-van-fo-893-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/08/rem-cuon-hoa-van-fo-893-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn hoa văn FO-893 Hàn Quốc" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cuon-hoa-van-fo-893-korea/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cuốn hoa văn FO-893 Korea</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>780.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>620.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cuon-c-322/" aria-label="Rèm cuốn C-332">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn C-322 cao cấp" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-322-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-322-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn C-322 cao cấp" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cuon-c-322/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cuốn C-332</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>345.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cuon-hoa-van-rb-905/" aria-label="Rèm cuốn hoa văn RB-905">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn hoa văn RB-905" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-hoa-van-rb-905-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-hoa-van-rb-905-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn hoa văn RB-905" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cuon-hoa-van-rb-905/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cuốn hoa văn RB-905</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>420.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cuon-hoa-van-rb-906/" aria-label="Rèm cuốn hoa văn RB-906">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn hoa văn RB-906" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-hoa-van-rb-906-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-hoa-van-rb-906-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn hoa văn RB-906" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cuon-hoa-van-rb-906/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cuốn hoa văn RB-906</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>420.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cuon-c-553/" aria-label="Rèm cuốn C-553">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn C-553" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-553-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-553-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-553-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-553-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn C-553" srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-553-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-553-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cuon-c-553/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cuốn C-553</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>365.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cuon-c-550/" aria-label="Rèm cuốn C-550">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn C-550" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-550-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-550-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-550-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-550-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn C-550" srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-550-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-c-550-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cuon-c-550/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cuốn C-550</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>365.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            	        </div>
		</div>

		
<style>
#section_1007371646 {
  padding-top: 10px;
  padding-bottom: 10px;
}
</style>
	</section>
	
	<section class="section" id="section_930479282">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			
<div class="container section-title-container" ><h2 class="section-title section-title-bold-center"><b></b><span class="section-title-main" style="font-size:90%;">Rèm Lá Dọc</span><b></b></h2></div>

  
    <div class="row  equalize-box large-columns-4 medium-columns-3 small-columns-2 row-small slider row-slider slider-nav-reveal slider-nav-push"  data-flickity-options='{"imagesLoaded": true, "groupCells": "100%", "dragThreshold" : 5, "cellAlign": "left","wrapAround": true,"prevNextButtons": true,"percentPosition": true,"pageDots": false, "rightToLeft": false, "autoPlay" : false}'>

  	
	     
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-la-doc-a-705/" aria-label="Rèm lá dọc A-705">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm lá dọc A-705" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-705-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-705-275x330.jpg 275w, https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-705-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-705-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-705-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm lá dọc A-705" srcset="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-705-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-705-275x330.jpg 275w, https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-705-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-la-doc-a-705/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm lá dọc A-705</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>195.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-la-doc-a-704/" aria-label="Rèm lá dọc A-704">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm lá dọc A-704" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-704-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-704-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-704-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-704-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm lá dọc A-704" srcset="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-704-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-a-704-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-la-doc-a-704/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm lá dọc A-704</a></p></div><div class="price-wrapper">
	<span class="price"><span class="woocommerce-Price-amount amount"><bdi>195.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-4%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-la-doc-a-334/" aria-label="Rèm lá dọc văn phòng mã A-334">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành sáo - Rèm lá dọc mã A 334" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-ld-a-334-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-ld-a-334-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-ld-a-334-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-ld-a-334-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành sáo - Rèm lá dọc mã A 334" srcset="https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-ld-a-334-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/06/rem-la-doc-ld-a-334-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-la-doc-a-334/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm lá dọc văn phòng mã A-334</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>230.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>220.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-15%</span></div></div>
</div>
						<div class="product-small box has-hover box-bounce box-text-bottom">
							<div class="box-image" >
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-la-doc-a-703/" aria-label="Rèm sáo lá dọc A 703">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm lá dọc A 703 cho văn phòng" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-la-doc-a-703-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-la-doc-a-703-335x402.jpg 335w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-la-doc-a-703-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2019/07/rem-la-doc-a-703-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm lá dọc A 703 cho văn phòng" srcset="https://remcuahn.com/wp-content/uploads/2019/07/rem-la-doc-a-703-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2019/07/rem-la-doc-a-703-335x402.jpg 335w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center" >
								<div class="title-wrapper"><p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-la-doc-a-703/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm sáo lá dọc A 703</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>230.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>195.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            	        </div>
		</div>

		
<style>
#section_930479282 {
  padding-top: 10px;
  padding-bottom: 10px;
}
</style>
	</section>
	
	<section class="section" id="section_1458770579">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			
<div class="container section-title-container" ><h2 class="section-title section-title-bold-center"><b></b><span class="section-title-main" style="font-size:90%;">Danh Mục Rèm Cửa</span><b></b></h2></div>

  
    <div class="row large-columns-5 medium-columns-3 small-columns-2 row-small has-shadow row-box-shadow-1 row-box-shadow-3-hover slider row-slider slider-nav-simple slider-nav-outside slider-nav-push"  data-flickity-options='{"imagesLoaded": true, "groupCells": "100%", "dragThreshold" : 5, "cellAlign": "left","wrapAround": true,"prevNextButtons": true,"percentPosition": true,"pageDots": false, "rightToLeft": false, "autoPlay" : false}'>

          <div class="product-category col" >
            <div class="col-inner">
              <a href="https://remcuahn.com/danh-muc/rem-cau-vong/">                <div class="box box-category has-hover box-bounce ">
                <div class="box-image" >
                  <div class="image-cover" style="padding-top:230px;">
                  <img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" alt="Mẫu Rèm Cầu Vồng" width="300" height="300" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-247x296.jpg" /><noscript><img src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cau-vong-247x296.jpg" alt="Mẫu Rèm Cầu Vồng" width="300" height="300" /></noscript>                                                      </div>
                </div>
                <div class="box-text text-center is-small" style="background-color:rgb(255, 255, 255);">
                  <div class="box-text-inner">
                      <h5 class="uppercase header-title">
                              Mẫu Rèm Cầu Vồng                      </h5>
                                            <p class="is-xsmall uppercase count ">
	                      23 Sản phẩm                      </p>
                                            
                  </div>
                </div>
                </div>
            </a>            </div>
            </div>
                <div class="product-category col" >
            <div class="col-inner">
              <a href="https://remcuahn.com/danh-muc/rem-cuon-tranh/">                <div class="box box-category has-hover box-bounce ">
                <div class="box-image" >
                  <div class="image-cover" style="padding-top:230px;">
                  <img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" alt="Mẫu Rèm Cuốn Tranh" width="300" height="300" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-tranh-247x296.jpg" /><noscript><img src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-tranh-247x296.jpg" alt="Mẫu Rèm Cuốn Tranh" width="300" height="300" /></noscript>                                                      </div>
                </div>
                <div class="box-text text-center is-small" style="background-color:rgb(255, 255, 255);">
                  <div class="box-text-inner">
                      <h5 class="uppercase header-title">
                              Mẫu Rèm Cuốn Tranh                      </h5>
                                            <p class="is-xsmall uppercase count ">
	                      10 Sản phẩm                      </p>
                                            
                  </div>
                </div>
                </div>
            </a>            </div>
            </div>
                <div class="product-category col" >
            <div class="col-inner">
              <a href="https://remcuahn.com/danh-muc/mau-rem-hat-go/">                <div class="box box-category has-hover box-bounce ">
                <div class="box-image" >
                  <div class="image-cover" style="padding-top:230px;">
                  <img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" alt="Mẫu Rèm Hạt Gỗ" width="300" height="300" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/08/rem-hat-go-247x296.jpg" /><noscript><img src="https://remcuahn.com/wp-content/uploads/2021/08/rem-hat-go-247x296.jpg" alt="Mẫu Rèm Hạt Gỗ" width="300" height="300" /></noscript>                                                      </div>
                </div>
                <div class="box-text text-center is-small" style="background-color:rgb(255, 255, 255);">
                  <div class="box-text-inner">
                      <h5 class="uppercase header-title">
                              Mẫu Rèm Hạt Gỗ                      </h5>
                                            <p class="is-xsmall uppercase count ">
	                      5 Sản phẩm                      </p>
                                            
                  </div>
                </div>
                </div>
            </a>            </div>
            </div>
                <div class="product-category col" >
            <div class="col-inner">
              <a href="https://remcuahn.com/danh-muc/rem-la-doc/">                <div class="box box-category has-hover box-bounce ">
                <div class="box-image" >
                  <div class="image-cover" style="padding-top:230px;">
                  <img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" alt="Mẫu Rèm Lá Dọc" width="300" height="300" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-la-doc-247x296.jpg" /><noscript><img src="https://remcuahn.com/wp-content/uploads/2019/07/rem-la-doc-247x296.jpg" alt="Mẫu Rèm Lá Dọc" width="300" height="300" /></noscript>                                                      </div>
                </div>
                <div class="box-text text-center is-small" style="background-color:rgb(255, 255, 255);">
                  <div class="box-text-inner">
                      <h5 class="uppercase header-title">
                              Mẫu Rèm Lá Dọc                      </h5>
                                            <p class="is-xsmall uppercase count ">
	                      4 Sản phẩm                      </p>
                                            
                  </div>
                </div>
                </div>
            </a>            </div>
            </div>
                <div class="product-category col" >
            <div class="col-inner">
              <a href="https://remcuahn.com/danh-muc/rem-roman/">                <div class="box box-category has-hover box-bounce ">
                <div class="box-image" >
                  <div class="image-cover" style="padding-top:230px;">
                  <img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" alt="Mẫu Rèm Roman" width="300" height="300" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-vai-roman-247x296.jpg" /><noscript><img src="https://remcuahn.com/wp-content/uploads/2019/07/rem-vai-roman-247x296.jpg" alt="Mẫu Rèm Roman" width="300" height="300" /></noscript>                                                      </div>
                </div>
                <div class="box-text text-center is-small" style="background-color:rgb(255, 255, 255);">
                  <div class="box-text-inner">
                      <h5 class="uppercase header-title">
                              Mẫu Rèm Roman                      </h5>
                                            <p class="is-xsmall uppercase count ">
	                      20 Sản phẩm                      </p>
                                            
                  </div>
                </div>
                </div>
            </a>            </div>
            </div>
                <div class="product-category col" >
            <div class="col-inner">
              <a href="https://remcuahn.com/danh-muc/rem-sao-nhom/">                <div class="box box-category has-hover box-bounce ">
                <div class="box-image" >
                  <div class="image-cover" style="padding-top:230px;">
                  <img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" alt="Mẫu Rèm Sáo Nhôm" width="300" height="300" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-sao-nhom-247x296.jpg" /><noscript><img src="https://remcuahn.com/wp-content/uploads/2019/07/rem-sao-nhom-247x296.jpg" alt="Mẫu Rèm Sáo Nhôm" width="300" height="300" /></noscript>                                                      </div>
                </div>
                <div class="box-text text-center is-small" style="background-color:rgb(255, 255, 255);">
                  <div class="box-text-inner">
                      <h5 class="uppercase header-title">
                              Mẫu Rèm Sáo Nhôm                      </h5>
                                            <p class="is-xsmall uppercase count ">
	                      10 Sản phẩm                      </p>
                                            
                  </div>
                </div>
                </div>
            </a>            </div>
            </div>
                <div class="product-category col" >
            <div class="col-inner">
              <a href="https://remcuahn.com/danh-muc/rem-vai/">                <div class="box box-category has-hover box-bounce ">
                <div class="box-image" >
                  <div class="image-cover" style="padding-top:230px;">
                  <img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" alt="Mẫu Rèm Vải" width="300" height="300" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-vai-247x296.jpg" /><noscript><img src="https://remcuahn.com/wp-content/uploads/2019/07/rem-vai-247x296.jpg" alt="Mẫu Rèm Vải" width="300" height="300" /></noscript>                                                      </div>
                </div>
                <div class="box-text text-center is-small" style="background-color:rgb(255, 255, 255);">
                  <div class="box-text-inner">
                      <h5 class="uppercase header-title">
                              Mẫu Rèm Vải                      </h5>
                                            <p class="is-xsmall uppercase count ">
	                      25 Sản phẩm                      </p>
                                            
                  </div>
                </div>
                </div>
            </a>            </div>
            </div>
                <div class="product-category col" >
            <div class="col-inner">
              <a href="https://remcuahn.com/danh-muc/rem-cuon/">                <div class="box box-category has-hover box-bounce ">
                <div class="box-image" >
                  <div class="image-cover" style="padding-top:230px;">
                  <img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" alt="Rèm Cuốn - Màn Cuốn" width="300" height="300" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-247x296.jpg" /><noscript><img src="https://remcuahn.com/wp-content/uploads/2019/07/rem-cuon-247x296.jpg" alt="Rèm Cuốn - Màn Cuốn" width="300" height="300" /></noscript>                                                      </div>
                </div>
                <div class="box-text text-center is-small" style="background-color:rgb(255, 255, 255);">
                  <div class="box-text-inner">
                      <h5 class="uppercase header-title">
                              Rèm Cuốn - Màn Cuốn                      </h5>
                                            <p class="is-xsmall uppercase count ">
	                      10 Sản phẩm                      </p>
                                            
                  </div>
                </div>
                </div>
            </a>            </div>
            </div>
                <div class="product-category col" >
            <div class="col-inner">
              <a href="https://remcuahn.com/danh-muc/rem-go/">                <div class="box box-category has-hover box-bounce ">
                <div class="box-image" >
                  <div class="image-cover" style="padding-top:230px;">
                  <img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" alt="Rèm Gỗ - Mành Gỗ" width="300" height="300" data-lazy-src="https://remcuahn.com/wp-content/uploads/2019/07/rem-go-247x296.jpg" /><noscript><img src="https://remcuahn.com/wp-content/uploads/2019/07/rem-go-247x296.jpg" alt="Rèm Gỗ - Mành Gỗ" width="300" height="300" /></noscript>                                                      </div>
                </div>
                <div class="box-text text-center is-small" style="background-color:rgb(255, 255, 255);">
                  <div class="box-text-inner">
                      <h5 class="uppercase header-title">
                              Rèm Gỗ - Mành Gỗ                      </h5>
                                            <p class="is-xsmall uppercase count ">
	                      9 Sản phẩm                      </p>
                                            
                  </div>
                </div>
                </div>
            </a>            </div>
            </div>
        </div>
<div class="container section-title-container" ><h2 class="section-title section-title-bold-center"><b></b><span class="section-title-main" style="font-size:90%;">Sản Phẩm Rèm Cửa Giảm Giá</span><b></b></h2></div>

  
    <div class="row  equalize-box large-columns-2 medium-columns- small-columns- row-small has-shadow row-box-shadow-2 slider row-slider slider-nav-simple slider-nav-outside"  data-flickity-options='{"imagesLoaded": true, "groupCells": "100%", "dragThreshold" : 5, "cellAlign": "left","wrapAround": true,"prevNextButtons": true,"percentPosition": true,"pageDots": false, "rightToLeft": false, "autoPlay" : 6000}'>

  	
	     
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-30%</span></div></div>
</div>
						<div class="product-small box has-hover box-vertical box-text-bottom">
							<div class="box-image" style="width:50%;">
								<div class="" >
									<a href="https://remcuahn.com/san-pham/manh-dung-klimt-elise-han-quoc/" aria-label="Mành đứng KLIMT, ELISE Hàn Quốc">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành dọc Hàn Quốc" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/12/manh-doc-han-quoc-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/12/manh-doc-han-quoc-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành dọc Hàn Quốc" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center is-large" style="background-color:rgb(255, 255, 255);">
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/manh-dung-klimt-elise-han-quoc/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Mành đứng KLIMT, ELISE Hàn Quốc</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>2.300.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>1.610.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-25%</span></div></div>
</div>
						<div class="product-small box has-hover box-vertical box-text-bottom">
							<div class="box-image" style="width:50%;">
								<div class="" >
									<a href="https://remcuahn.com/san-pham/manh-sao-ngang-3-lop-han-quoc/" aria-label="Mành sáo ngang 3 lớp Hàn Quốc">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành sáo ngang 3 lớp Hàn Quốc" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/12/manh-ngang-3-lop-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/12/manh-ngang-3-lop-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành sáo ngang 3 lớp Hàn Quốc" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center is-large" style="background-color:rgb(255, 255, 255);">
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Cầu Vồng		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/manh-sao-ngang-3-lop-han-quoc/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Mành sáo ngang 3 lớp Hàn Quốc</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>1.180.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>885.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-19%</span></div></div>
</div>
						<div class="product-small box has-hover box-vertical box-text-bottom">
							<div class="box-image" style="width:50%;">
								<div class="" >
									<a href="https://remcuahn.com/san-pham/manh-cuon-chong-nang-han-quoc/" aria-label="Mành cuốn chống nắng Hàn Quốc">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành cuốn Thanh Nhàn" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-340x408.jpg 340w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành cuốn Thanh Nhàn" srcset="https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/11/manh-cuon-thanh-nhan-340x408.jpg 340w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center is-large" style="background-color:rgb(255, 255, 255);">
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Rèm Cuốn - Màn Cuốn		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/manh-cuon-chong-nang-han-quoc/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Mành cuốn chống nắng Hàn Quốc</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>740.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>600.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-25%</span></div></div>
</div>
						<div class="product-small box has-hover box-vertical box-text-bottom">
							<div class="box-image" style="width:50%;">
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cua-cau-vong-modero-ma-bali-han-quoc/" aria-label="Rèm cửa cầu vồng Modero mã Bali Hàn Quốc">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa cầu vồng Modero mã Bali Hàn Quốc" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-bali-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-bali-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cửa cầu vồng Modero mã Bali Hàn Quốc" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center is-large" style="background-color:rgb(255, 255, 255);">
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Cầu Vồng		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cua-cau-vong-modero-ma-bali-han-quoc/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cửa cầu vồng Modero mã Bali Hàn Quốc</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>1.020.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>765.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-17%</span></div></div>
</div>
						<div class="product-small box has-hover box-vertical box-text-bottom">
							<div class="box-image" style="width:50%;">
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-vai-ni-van-tn950-phong-ngu/" aria-label="Rèm vải nỉ vân TN950 phòng ngủ">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải nỉ vân RV950-9" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-vai-ni-van-rv-950-9-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-vai-ni-van-rv-950-9-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm vải nỉ vân RV950-9" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center is-large" style="background-color:rgb(255, 255, 255);">
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Vải Một Màu		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-vai-ni-van-tn950-phong-ngu/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm vải nỉ vân TN950 phòng ngủ</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>600.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>500.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-25%</span></div></div>
</div>
						<div class="product-small box has-hover box-vertical box-text-bottom">
							<div class="box-image" style="width:50%;">
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cuon-han-quoc-porsche/" aria-label="Rèm cuốn Hàn Quốc PORSCHE">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn Hàn Quốc PORSCHE PO352" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cuon-han-quoc-porsche-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cuon-han-quoc-porsche-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cuốn Hàn Quốc PORSCHE PO352" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center is-large" style="background-color:rgb(255, 255, 255);">
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Cầu Vồng		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cuon-han-quoc-porsche/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cuốn Hàn Quốc PORSCHE</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>1.280.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>960.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-25%</span></div></div>
</div>
						<div class="product-small box has-hover box-vertical box-text-bottom">
							<div class="box-image" style="width:50%;">
								<div class="" >
									<a href="https://remcuahn.com/san-pham/manh-cau-vong-gia-re-hillary/" aria-label="Mành cầu vồng giá rẻ mã Hillary">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành cầu vồng Hillary Hàn Quốc" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-han-quoc-hillary-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-han-quoc-hillary-340x408.jpg 340w" data-lazy-sizes="(max-width: 247px) 100vw, 247px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-han-quoc-hillary-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-han-quoc-hillary-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Mành cầu vồng Hillary Hàn Quốc" srcset="https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-han-quoc-hillary-247x296.jpg 247w, https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-han-quoc-hillary-340x408.jpg 340w" sizes="(max-width: 247px) 100vw, 247px" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center is-large" style="background-color:rgb(255, 255, 255);">
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Cầu Vồng		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/manh-cau-vong-gia-re-hillary/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Mành cầu vồng giá rẻ mã Hillary</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>830.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>622.500<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            
						            	
	            	<div class="col" >
						<div class="col-inner">
						
<div class="badge-container absolute left top z-1">
		<div class="callout badge badge-circle"><div class="badge-inner secondary on-sale"><span class="onsale">-25%</span></div></div>
</div>
						<div class="product-small box has-hover box-vertical box-text-bottom">
							<div class="box-image" style="width:50%;">
								<div class="" >
									<a href="https://remcuahn.com/san-pham/rem-cau-vong-spacy/" aria-label="Rèm cầu vồng SPACY Modero">
										<img width="247" height="296" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20247%20296'%3E%3C/svg%3E" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng SPACY" data-lazy-src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-spacy-247x296.jpg" /><noscript><img width="247" height="296" src="https://remcuahn.com/wp-content/uploads/2020/08/rem-cau-vong-spacy-247x296.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="Rèm cầu vồng SPACY" /></noscript>									</a>
																		 								</div>
								<div class="image-tools top right show-on-hover">
																	</div>
																	<div class="image-tools grid-tools text-center hide-for-small bottom hover-slide-in show-on-hover">
																			</div>
																							</div>

							<div class="box-text text-center is-large" style="background-color:rgb(255, 255, 255);">
								<div class="title-wrapper">		<p class="category uppercase is-smaller no-text-overflow product-cat op-7">
			Mẫu Rèm Cầu Vồng		</p>
	<p class="name product-title woocommerce-loop-product__title"><a href="https://remcuahn.com/san-pham/rem-cau-vong-spacy/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">Rèm cầu vồng SPACY Modero</a></p></div><div class="price-wrapper">
	<span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><bdi>890.000<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></del> <ins><span class="woocommerce-Price-amount amount"><bdi>667.500<span class="woocommerce-Price-currencySymbol">&#8363;</span></bdi></span></ins></span>
</div>							</div>
						</div>
						</div>
					</div>
						            	        </div>
		</div>

		
<style>
#section_1458770579 {
  padding-top: 10px;
  padding-bottom: 10px;
}
</style>
	</section>
	

  <div class="banner has-hover" id="banner-1466250146">
          <div class="banner-inner fill">
        <div class="banner-bg fill" >
            <div class="bg fill bg-fill bg-loaded"></div>
                        <div class="overlay"></div>            
            <div class="effect-sliding-glass bg-effect fill no-click"></div>        </div>
        <div class="banner-layers container">
            <div class="fill banner-link"></div>            
   <div id="text-box-2034007177" class="text-box banner-layer x50 md-x50 lg-x50 y100 md-y100 lg-y95 res-text">
                                <div class="text-box-content text dark">
              
              <div class="text-inner text-center">
                  
<h2 class="uppercase"><span style="font-size: 100%;">Nội Thất Thanh Nhàn</span></h2>
<p class="lead">Hãy để chúng tôi giúp bạn. Vì chúng tôi muốn không gian cửa bạn đẹp và tỏa sáng.!</p>
<a href="https://remcuahn.com/tu-van-rem-cua/" target="_self" class="button white"  style="border-radius:99px;">
    <span>Tìm Hiểu Thêm</span>
  </a>

<a href="https://remcuahn.com/rem-cua/" target="_self" class="button white"  style="border-radius:99px;">
    <span>Ghé Thăm Cửa Hàng</span>
  </a>

<p><span style="color: #ffffff; font-size: 120%;"><strong>ĐĂNG KÝ NHẬN BẢN TIN</strong></span><br />
<div role="form" class="wpcf7" id="wpcf7-f3250-p3229-o1" lang="vi" dir="ltr">
<div class="screen-reader-response"><p role="status" aria-live="polite" aria-atomic="true"></p> <ul></ul></div>
<form action="/#wpcf7-f3250-p3229-o1" method="post" class="wpcf7-form init" novalidate="novalidate" data-status="init">
<div style="display: none;">
<input type="hidden" name="_wpcf7" value="3250" />
<input type="hidden" name="_wpcf7_version" value="5.4.2" />
<input type="hidden" name="_wpcf7_locale" value="vi" />
<input type="hidden" name="_wpcf7_unit_tag" value="wpcf7-f3250-p3229-o1" />
<input type="hidden" name="_wpcf7_container_post" value="3229" />
<input type="hidden" name="_wpcf7_posted_data_hash" value="" />
</div>
<div class="flex-row form-flat medium-flex-wrap">
<div class="flex-col flex-grow>
        <span class="wpcf7-form-control-wrap your-email"><input type="email" name="your-email" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-email wpcf7-validates-as-required wpcf7-validates-as-email" aria-required="true" aria-invalid="false" placeholder="Địa chỉ email (*)" /></span>
    </div>
<div class="flex-col ml-half">
        <input type="submit" value="Đăng ký" class="wpcf7-form-control wpcf7-submit button" />
    </div>
</div>
<div class="wpcf7-response-output" aria-hidden="true"></div></form></div>
              </div>
           </div>
                            
<style>
#text-box-2034007177 {
  width: 76%;
}
#text-box-2034007177 .text-box-content {
  font-size: 100%;
}
@media (min-width:550px) {
  #text-box-2034007177 {
    width: 91%;
  }
}
@media (min-width:850px) {
  #text-box-2034007177 {
    width: 69%;
  }
}
</style>
    </div>
 
        </div>
      </div>

            
<style>
#banner-1466250146 {
  padding-top: 420px;
  background-color: rgb(80, 80, 80);
}
#banner-1466250146 .bg.bg-loaded {
  background-image: url(https://remcuahn.com/wp-content/uploads/2021/08/rem-cua-cao-cap.jpg);
}
#banner-1466250146 .overlay {
  background-color: rgba(0, 0, 0, 0.49);
}
#banner-1466250146 .bg {
  background-position: 28% 56%;
}
</style>
  </div>


	<section class="section" id="section_1992825464">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			
<div class="row"  id="row-235269261">

	<div id="col-1471437153" class="col small-12 large-12"  >
				<div class="col-inner"  >
			
			
<div class="row"  id="row-915715765">

	<div id="col-911348846" class="col medium-4 small-12 large-4"  >
				<div class="col-inner"  >
			
			
	<div id="text-1396808968" class="text">
		
<p class="uppercase" style="text-align: center;"><span style="font-size: 110%;">hỗ trợ 24/7</span></p>
<p>Chúng tôi sẵn sàng phục vụ Quý khách hàng tất cả các ngày trong tuần.<br />
		
<style>
#text-1396808968 {
  text-align: center;
}
@media (min-width:850px) {
  #text-1396808968 {
    text-align: center;
  }
}
</style>
	</div>
	
		</div>
					</div>

	

	<div id="col-1883199405" class="col medium-4 small-12 large-4"  >
				<div class="col-inner"  >
			
			
	<div id="text-3029524706" class="text">
		
<p class="uppercase" style="text-align: center;"><span style="font-size: 110%;">thi công nhanh</span></p>
<p>Thời gian đặt hàng và lắp đặt hoàn chỉnh trong 3 ngày.<br />
		
<style>
#text-3029524706 {
  text-align: center;
}
@media (min-width:850px) {
  #text-3029524706 {
    text-align: center;
  }
}
</style>
	</div>
	
		</div>
					</div>

	

	<div id="col-1091281088" class="col medium-4 small-12 large-4"  >
				<div class="col-inner"  >
			
			
	<div id="text-4238306148" class="text">
		
<p class="uppercase" style="text-align: center;"><span style="font-size: 110%;">bảo hành 12t</span></p>
<p>Thời hạn bảo hành từ 12T tùy theo sản phẩm. Bảo trì trọn đời.<br />
		
<style>
#text-4238306148 {
  text-align: center;
}
@media (min-width:850px) {
  #text-4238306148 {
    text-align: center;
  }
}
</style>
	</div>
	
		</div>
					</div>

	
</div>
<div class="container section-title-container" ><h2 class="section-title section-title-bold-center"><b></b><span class="section-title-main" style="font-size:90%;">Bài Viết Chia Sẻ Kinh Nghiệm Chọn Mành Rèm</span><b></b></h2></div>

  
    <div class="row large-columns-3 medium-columns-2 small-columns-1 row-small has-shadow row-box-shadow-1 slider row-slider slider-nav-simple"  data-flickity-options='{"imagesLoaded": true, "groupCells": "100%", "dragThreshold" : 5, "cellAlign": "left","wrapAround": true,"prevNextButtons": true,"percentPosition": true,"pageDots": false, "rightToLeft": false, "autoPlay" : false}'>

  		<div class="col post-item" >
			<div class="col-inner">
			<a href="https://remcuahn.com/rem-vai-2-lop-chat-lua-dep-sang-trong-tai-ha-noi/" class="plain">
				<div class="box box-overlay dark box-text-bottom box-blog-post has-hover">
            					<div class="box-image" >
  						<div class="image-cover" style="padding-top:100%;">
  							<img width="680" height="478" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20680%20478'%3E%3C/svg%3E" class="attachment-medium size-medium wp-post-image" alt="Rèm vải 2 lớp chất lụa đẹp sang trọng tại Hà Nội" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/09/rem-vai-dep-2-lop-phong-khach.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/09/rem-vai-dep-2-lop-phong-khach-510x359.jpg 510w" data-lazy-sizes="(max-width: 680px) 100vw, 680px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/09/rem-vai-dep-2-lop-phong-khach.jpg" /><noscript><img width="680" height="478" src="https://remcuahn.com/wp-content/uploads/2021/09/rem-vai-dep-2-lop-phong-khach.jpg" class="attachment-medium size-medium wp-post-image" alt="Rèm vải 2 lớp chất lụa đẹp sang trọng tại Hà Nội" srcset="https://remcuahn.com/wp-content/uploads/2021/09/rem-vai-dep-2-lop-phong-khach.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/09/rem-vai-dep-2-lop-phong-khach-510x359.jpg 510w" sizes="(max-width: 680px) 100vw, 680px" /></noscript>  							<div class="overlay" style="background-color: rgba(0,0,0,.25)"></div>  							  						</div>
  						  					</div>
          					<div class="box-text show-on-hover hover-bounce text-center" >
					<div class="box-text-inner blog-post-inner">

					
										<h5 class="post-title is-large ">Rèm vải 2 lớp chất lụa đẹp sang trọng tại Hà Nội</h5>
										<div class="is-divider"></div>
										<p class="from_the_blog_excerpt ">Rèm vải 2 lớp chất lụa tổng hợp loại vân xước 1 màu trang hoàng [...]					</p>
					                    
											<button href="https://remcuahn.com/rem-vai-2-lop-chat-lua-dep-sang-trong-tai-ha-noi/" class="button  is-outline is-small mb-0">
							Đọc Thêm						</button>
					
					
					</div>
					</div>
																<div class="badge absolute top post-date badge-outline">
							<div class="badge-inner">
								<span class="post-date-day">18</span><br>
								<span class="post-date-month is-xsmall">Th9</span>
							</div>
						</div>
									</div>
				</a>
			</div>
		</div>
		<div class="col post-item" >
			<div class="col-inner">
			<a href="https://remcuahn.com/mau-rem-hat-go-phong-tho-dep-tai-ha-noi/" class="plain">
				<div class="box box-overlay dark box-text-bottom box-blog-post has-hover">
            					<div class="box-image" >
  						<div class="image-cover" style="padding-top:100%;">
  							<img width="680" height="510" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20680%20510'%3E%3C/svg%3E" class="attachment-medium size-medium wp-post-image" alt="Rèm hạt gỗ phong thủy" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/08/rem-hat-go-phong-thuy.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/08/rem-hat-go-phong-thuy-510x383.jpg 510w" data-lazy-sizes="(max-width: 680px) 100vw, 680px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/08/rem-hat-go-phong-thuy.jpg" /><noscript><img width="680" height="510" src="https://remcuahn.com/wp-content/uploads/2021/08/rem-hat-go-phong-thuy.jpg" class="attachment-medium size-medium wp-post-image" alt="Rèm hạt gỗ phong thủy" srcset="https://remcuahn.com/wp-content/uploads/2021/08/rem-hat-go-phong-thuy.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/08/rem-hat-go-phong-thuy-510x383.jpg 510w" sizes="(max-width: 680px) 100vw, 680px" /></noscript>  							<div class="overlay" style="background-color: rgba(0,0,0,.25)"></div>  							  						</div>
  						  					</div>
          					<div class="box-text show-on-hover hover-bounce text-center" >
					<div class="box-text-inner blog-post-inner">

					
										<h5 class="post-title is-large ">Mẫu rèm hạt gỗ phòng thờ đẹp tại Hà Nội</h5>
										<div class="is-divider"></div>
										<p class="from_the_blog_excerpt ">Xưởng sản xuất, phân phối bán sỉ, bán lẻ rèm mành hạt gỗ Hương, gỗ [...]					</p>
					                    
											<button href="https://remcuahn.com/mau-rem-hat-go-phong-tho-dep-tai-ha-noi/" class="button  is-outline is-small mb-0">
							Đọc Thêm						</button>
					
					
					</div>
					</div>
																<div class="badge absolute top post-date badge-outline">
							<div class="badge-inner">
								<span class="post-date-day">07</span><br>
								<span class="post-date-month is-xsmall">Th8</span>
							</div>
						</div>
									</div>
				</a>
			</div>
		</div>
		<div class="col post-item" >
			<div class="col-inner">
			<a href="https://remcuahn.com/mau-rem-la-doc-van-phong-dep-tai-ha-noi/" class="plain">
				<div class="box box-overlay dark box-text-bottom box-blog-post has-hover">
            					<div class="box-image" >
  						<div class="image-cover" style="padding-top:100%;">
  							<img width="680" height="544" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20680%20544'%3E%3C/svg%3E" class="attachment-medium size-medium wp-post-image" alt="Rèm lá dọc văn phòng" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/08/rem-la-doc-van-phong.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/08/rem-la-doc-van-phong-510x408.jpg 510w" data-lazy-sizes="(max-width: 680px) 100vw, 680px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/08/rem-la-doc-van-phong.jpg" /><noscript><img width="680" height="544" src="https://remcuahn.com/wp-content/uploads/2021/08/rem-la-doc-van-phong.jpg" class="attachment-medium size-medium wp-post-image" alt="Rèm lá dọc văn phòng" srcset="https://remcuahn.com/wp-content/uploads/2021/08/rem-la-doc-van-phong.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/08/rem-la-doc-van-phong-510x408.jpg 510w" sizes="(max-width: 680px) 100vw, 680px" /></noscript>  							<div class="overlay" style="background-color: rgba(0,0,0,.25)"></div>  							  						</div>
  						  					</div>
          					<div class="box-text show-on-hover hover-bounce text-center" >
					<div class="box-text-inner blog-post-inner">

					
										<h5 class="post-title is-large ">Mẫu rèm lá dọc văn phòng đẹp tại Hà Nội</h5>
										<div class="is-divider"></div>
										<p class="from_the_blog_excerpt ">Mẫu màn sáo, rèm lá (lật) dọc văn phòng đẹp nhất cho cửa văn phòng, [...]					</p>
					                    
											<button href="https://remcuahn.com/mau-rem-la-doc-van-phong-dep-tai-ha-noi/" class="button  is-outline is-small mb-0">
							Đọc Thêm						</button>
					
					
					</div>
					</div>
																<div class="badge absolute top post-date badge-outline">
							<div class="badge-inner">
								<span class="post-date-day">04</span><br>
								<span class="post-date-month is-xsmall">Th8</span>
							</div>
						</div>
									</div>
				</a>
			</div>
		</div>
		<div class="col post-item" >
			<div class="col-inner">
			<a href="https://remcuahn.com/mau-rem-cua-dep-phong-khach-phong-ngu-tai-quan-ha-dong/" class="plain">
				<div class="box box-overlay dark box-text-bottom box-blog-post has-hover">
            					<div class="box-image" >
  						<div class="image-cover" style="padding-top:100%;">
  							<img width="720" height="544" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20720%20544'%3E%3C/svg%3E" class="attachment-medium size-medium wp-post-image" alt="Mẫu rèm cửa đẹp phòng khách" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/07/mau-rem-cua-dep-phong-khach.jpg 720w, https://remcuahn.com/wp-content/uploads/2021/07/mau-rem-cua-dep-phong-khach-510x385.jpg 510w" data-lazy-sizes="(max-width: 720px) 100vw, 720px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/07/mau-rem-cua-dep-phong-khach.jpg" /><noscript><img width="720" height="544" src="https://remcuahn.com/wp-content/uploads/2021/07/mau-rem-cua-dep-phong-khach.jpg" class="attachment-medium size-medium wp-post-image" alt="Mẫu rèm cửa đẹp phòng khách" srcset="https://remcuahn.com/wp-content/uploads/2021/07/mau-rem-cua-dep-phong-khach.jpg 720w, https://remcuahn.com/wp-content/uploads/2021/07/mau-rem-cua-dep-phong-khach-510x385.jpg 510w" sizes="(max-width: 720px) 100vw, 720px" /></noscript>  							<div class="overlay" style="background-color: rgba(0,0,0,.25)"></div>  							  						</div>
  						  					</div>
          					<div class="box-text show-on-hover hover-bounce text-center" >
					<div class="box-text-inner blog-post-inner">

					
										<h5 class="post-title is-large ">Mẫu rèm cửa đẹp phòng khách, phòng ngủ tại quận Hà Đông</h5>
										<div class="is-divider"></div>
										<p class="from_the_blog_excerpt ">Để chọn được mẫu rèm cửa đi, cửa sổ đẹp, sang trọng tối ưu, phù [...]					</p>
					                    
											<button href="https://remcuahn.com/mau-rem-cua-dep-phong-khach-phong-ngu-tai-quan-ha-dong/" class="button  is-outline is-small mb-0">
							Đọc Thêm						</button>
					
					
					</div>
					</div>
																<div class="badge absolute top post-date badge-outline">
							<div class="badge-inner">
								<span class="post-date-day">29</span><br>
								<span class="post-date-month is-xsmall">Th7</span>
							</div>
						</div>
									</div>
				</a>
			</div>
		</div>
		<div class="col post-item" >
			<div class="col-inner">
			<a href="https://remcuahn.com/rem-cua-so-cau-vong-gia-re-o-quan-thanh-xuan-ha-noi/" class="plain">
				<div class="box box-overlay dark box-text-bottom box-blog-post has-hover">
            					<div class="box-image" >
  						<div class="image-cover" style="padding-top:100%;">
  							<img width="1280" height="960" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%201280%20960'%3E%3C/svg%3E" class="attachment-medium size-medium wp-post-image" alt="Rèm cửa sổ cầu vồng" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/07/rem-cua-so-cau-vong.jpg 1280w, https://remcuahn.com/wp-content/uploads/2021/07/rem-cua-so-cau-vong-510x383.jpg 510w, https://remcuahn.com/wp-content/uploads/2021/07/rem-cua-so-cau-vong-768x576.jpg 768w" data-lazy-sizes="(max-width: 1280px) 100vw, 1280px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/07/rem-cua-so-cau-vong.jpg" /><noscript><img width="1280" height="960" src="https://remcuahn.com/wp-content/uploads/2021/07/rem-cua-so-cau-vong.jpg" class="attachment-medium size-medium wp-post-image" alt="Rèm cửa sổ cầu vồng" srcset="https://remcuahn.com/wp-content/uploads/2021/07/rem-cua-so-cau-vong.jpg 1280w, https://remcuahn.com/wp-content/uploads/2021/07/rem-cua-so-cau-vong-510x383.jpg 510w, https://remcuahn.com/wp-content/uploads/2021/07/rem-cua-so-cau-vong-768x576.jpg 768w" sizes="(max-width: 1280px) 100vw, 1280px" /></noscript>  							<div class="overlay" style="background-color: rgba(0,0,0,.25)"></div>  							  						</div>
  						  					</div>
          					<div class="box-text show-on-hover hover-bounce text-center" >
					<div class="box-text-inner blog-post-inner">

					
										<h5 class="post-title is-large ">Rèm cửa sổ cầu vồng giá rẻ ở quận Thanh Xuân Hà Nội</h5>
										<div class="is-divider"></div>
										<p class="from_the_blog_excerpt ">Màn rèm cầu vồng xuất xứ chính hãng Hàn Quốc Grace Home cho cửa sổ [...]					</p>
					                    
											<button href="https://remcuahn.com/rem-cua-so-cau-vong-gia-re-o-quan-thanh-xuan-ha-noi/" class="button  is-outline is-small mb-0">
							Đọc Thêm						</button>
					
					
					</div>
					</div>
																<div class="badge absolute top post-date badge-outline">
							<div class="badge-inner">
								<span class="post-date-day">27</span><br>
								<span class="post-date-month is-xsmall">Th7</span>
							</div>
						</div>
									</div>
				</a>
			</div>
		</div>
		<div class="col post-item" >
			<div class="col-inner">
			<a href="https://remcuahn.com/rem-roman-xep-lop-dep-voi-gia-re-ha-noi/" class="plain">
				<div class="box box-overlay dark box-text-bottom box-blog-post has-hover">
            					<div class="box-image" >
  						<div class="image-cover" style="padding-top:100%;">
  							<img width="720" height="540" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20720%20540'%3E%3C/svg%3E" class="attachment-medium size-medium wp-post-image" alt="Mẫu rèm cửa sổ phòng ngủ đẹp" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/06/mau-rem-cua-so-phong-ngu-dep.jpg 720w, https://remcuahn.com/wp-content/uploads/2021/06/mau-rem-cua-so-phong-ngu-dep-510x383.jpg 510w" data-lazy-sizes="(max-width: 720px) 100vw, 720px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/06/mau-rem-cua-so-phong-ngu-dep.jpg" /><noscript><img width="720" height="540" src="https://remcuahn.com/wp-content/uploads/2021/06/mau-rem-cua-so-phong-ngu-dep.jpg" class="attachment-medium size-medium wp-post-image" alt="Mẫu rèm cửa sổ phòng ngủ đẹp" srcset="https://remcuahn.com/wp-content/uploads/2021/06/mau-rem-cua-so-phong-ngu-dep.jpg 720w, https://remcuahn.com/wp-content/uploads/2021/06/mau-rem-cua-so-phong-ngu-dep-510x383.jpg 510w" sizes="(max-width: 720px) 100vw, 720px" /></noscript>  							<div class="overlay" style="background-color: rgba(0,0,0,.25)"></div>  							  						</div>
  						  					</div>
          					<div class="box-text show-on-hover hover-bounce text-center" >
					<div class="box-text-inner blog-post-inner">

					
										<h5 class="post-title is-large ">Rèm roman xếp lớp đẹp với giá rẻ Hà Nội</h5>
										<div class="is-divider"></div>
										<p class="from_the_blog_excerpt ">Rèm roman kẹp, mẫu roman 2 lớp đẹp giá rẻ, rèm xếp lớp, màn cửa [...]					</p>
					                    
											<button href="https://remcuahn.com/rem-roman-xep-lop-dep-voi-gia-re-ha-noi/" class="button  is-outline is-small mb-0">
							Đọc Thêm						</button>
					
					
					</div>
					</div>
																<div class="badge absolute top post-date badge-outline">
							<div class="badge-inner">
								<span class="post-date-day">06</span><br>
								<span class="post-date-month is-xsmall">Th6</span>
							</div>
						</div>
									</div>
				</a>
			</div>
		</div>
		<div class="col post-item" >
			<div class="col-inner">
			<a href="https://remcuahn.com/man-sao-nhom-phong-tam-tai-quan-ha-dong/" class="plain">
				<div class="box box-overlay dark box-text-bottom box-blog-post has-hover">
            					<div class="box-image" >
  						<div class="image-cover" style="padding-top:100%;">
  							<img width="680" height="510" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20680%20510'%3E%3C/svg%3E" class="attachment-medium size-medium wp-post-image" alt="Màn rèm sáo nhôm phòng tắm" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/05/man-rem-sao-nhom-phong-tam.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/05/man-rem-sao-nhom-phong-tam-510x383.jpg 510w" data-lazy-sizes="(max-width: 680px) 100vw, 680px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/05/man-rem-sao-nhom-phong-tam.jpg" /><noscript><img width="680" height="510" src="https://remcuahn.com/wp-content/uploads/2021/05/man-rem-sao-nhom-phong-tam.jpg" class="attachment-medium size-medium wp-post-image" alt="Màn rèm sáo nhôm phòng tắm" srcset="https://remcuahn.com/wp-content/uploads/2021/05/man-rem-sao-nhom-phong-tam.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/05/man-rem-sao-nhom-phong-tam-510x383.jpg 510w" sizes="(max-width: 680px) 100vw, 680px" /></noscript>  							<div class="overlay" style="background-color: rgba(0,0,0,.25)"></div>  							  						</div>
  						  					</div>
          					<div class="box-text show-on-hover hover-bounce text-center" >
					<div class="box-text-inner blog-post-inner">

					
										<h5 class="post-title is-large ">Màn sáo nhôm phòng tắm tại quận Hà Đông</h5>
										<div class="is-divider"></div>
										<p class="from_the_blog_excerpt ">Rèm màn sáo nhôm, mành sáo ngang có cấu tạo giống rèm sáo gỗ, có [...]					</p>
					                    
											<button href="https://remcuahn.com/man-sao-nhom-phong-tam-tai-quan-ha-dong/" class="button  is-outline is-small mb-0">
							Đọc Thêm						</button>
					
					
					</div>
					</div>
																<div class="badge absolute top post-date badge-outline">
							<div class="badge-inner">
								<span class="post-date-day">09</span><br>
								<span class="post-date-month is-xsmall">Th5</span>
							</div>
						</div>
									</div>
				</a>
			</div>
		</div>
		<div class="col post-item" >
			<div class="col-inner">
			<a href="https://remcuahn.com/rem-vai-ngan-phong-lanh-dieu-hoa-gia-dinh-ha-dong/" class="plain">
				<div class="box box-overlay dark box-text-bottom box-blog-post has-hover">
            					<div class="box-image" >
  						<div class="image-cover" style="padding-top:100%;">
  							<img width="680" height="544" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20680%20544'%3E%3C/svg%3E" class="attachment-medium size-medium wp-post-image" alt="Rèm ngăn lạnh điều hòa" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/04/rem-vai-ngan-phong-may-lanh-dieu-hoa.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/04/rem-vai-ngan-phong-may-lanh-dieu-hoa-510x408.jpg 510w" data-lazy-sizes="(max-width: 680px) 100vw, 680px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/04/rem-vai-ngan-phong-may-lanh-dieu-hoa.jpg" /><noscript><img width="680" height="544" src="https://remcuahn.com/wp-content/uploads/2021/04/rem-vai-ngan-phong-may-lanh-dieu-hoa.jpg" class="attachment-medium size-medium wp-post-image" alt="Rèm ngăn lạnh điều hòa" srcset="https://remcuahn.com/wp-content/uploads/2021/04/rem-vai-ngan-phong-may-lanh-dieu-hoa.jpg 680w, https://remcuahn.com/wp-content/uploads/2021/04/rem-vai-ngan-phong-may-lanh-dieu-hoa-510x408.jpg 510w" sizes="(max-width: 680px) 100vw, 680px" /></noscript>  							<div class="overlay" style="background-color: rgba(0,0,0,.25)"></div>  							  						</div>
  						  					</div>
          					<div class="box-text show-on-hover hover-bounce text-center" >
					<div class="box-text-inner blog-post-inner">

					
										<h5 class="post-title is-large ">Rèm vải ngăn phòng lạnh điều hòa gia đình Hà Đông</h5>
										<div class="is-divider"></div>
										<p class="from_the_blog_excerpt ">Rèm vải ngăn phòng máy lạnh điều hòa trong gia đình &#8211; Giải pháp màn [...]					</p>
					                    
											<button href="https://remcuahn.com/rem-vai-ngan-phong-lanh-dieu-hoa-gia-dinh-ha-dong/" class="button  is-outline is-small mb-0">
							Đọc Thêm						</button>
					
					
					</div>
					</div>
																<div class="badge absolute top post-date badge-outline">
							<div class="badge-inner">
								<span class="post-date-day">16</span><br>
								<span class="post-date-month is-xsmall">Th4</span>
							</div>
						</div>
									</div>
				</a>
			</div>
		</div>
</div>
<p>Rèm Thanh Nhàn là đơn vị hàng đầu trực tiếp sản xuất, lắp đặt các loại rèm mành cửa, cửa sổ đẹp, chất lượng, giá rẻ, uy tín, dịch vụ chuyên nghiệp. Là địa chỉ <b><i>uy tín –</i></b> <em><strong>tin cậy</strong></em> của mọi nhà.Sản phẩm, dịch vụ <i>rèm mành cửa sổ cho gia đình, văn phòng nổi bật như rèm vải đẹp, rèm vải 2 lớp, rèm xếp lớp, rèm vải nhật, rèm vải Hàn Quốc, rèm cầu vồng, rèm gỗ, mành nhựa, rèm cuốn chống nắng, rèm cuốn tranh, rèm cuốn, rèm lá dọc, rèm sáo nhôm</i>,… Với cam kết đem lại <b>lợi ích lớn nhất</b> cho quý khách hàngVới đội ngũ nhân viên ưu tú, nhiệt tình, kỹ thuật lành nghề, chuyên nghiệp, … Không ngừng vươn lên <em><strong>hoàn thiện sản phẩm và chất lượng dịch vụ</strong></em> giành được lòng tin và đánh giá cao của người tiêu dùng.</p>
		</div>
					</div>

	
</div>
		</div>

		
<style>
#section_1992825464 {
  padding-top: 30px;
  padding-bottom: 30px;
  background-color: rgb(244, 244, 244);
}
</style>
	</section>
	
		
				
</div>



</main>

<footer id="footer" class="footer-wrapper">

		<section class="section" id="section_728579558">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			

<div class="row"  id="row-1270060671">


	<div id="col-1346331836" class="col small-12 large-12"  >
				<div class="col-inner text-left"  >
			
			

	<div id="text-3168045256" class="text">
		

<p style="text-align: center;"><span style="color: #ffffff; font-size: 120%;">DANH MỤC PHỔ BIẾN</span></p>
		
<style>
#text-3168045256 {
  text-align: center;
}
</style>
	</div>
	
	<div id="gap-440136656" class="gap-element clearfix" style="display:block; height:auto;">
		
<style>
#gap-440136656 {
  padding-top: 10px;
}
</style>
	</div>
	

<div class="row row-collapse align-equal row-divided row-box-shadow-1 row-box-shadow-4-hover"  id="row-1015758727">


	<div id="col-370067368" class="col medium-4 small-12 large-2"  >
				<div class="col-inner"  >
			
			

<a href="https://remcuahn.com/danh-muc/rem-vai/" target="_self" class="button primary is-link is-small expand"  >
    <span>Rèm Vải</span>
  </a>



		</div>
					</div>

	

	<div id="col-1466920009" class="col medium-4 small-12 large-2"  >
				<div class="col-inner"  >
			
			

<a href="https://remcuahn.com/danh-muc/rem-roman/" target="_self" class="button primary is-link is-small expand"  >
    <span>Rèm ROMAN</span>
  </a>



		</div>
					</div>

	

	<div id="col-429953104" class="col medium-4 small-12 large-2"  >
				<div class="col-inner"  >
			
			

<a href="https://remcuahn.com/danh-muc/rem-cau-vong/" target="_self" class="button primary is-link is-small expand"  >
    <span>Rèm Cầu Vồng</span>
  </a>



		</div>
					</div>

	

	<div id="col-1211142163" class="col medium-4 small-12 large-2"  >
				<div class="col-inner"  >
			
			

<a href="https://remcuahn.com/danh-muc/rem-go/" target="_self" class="button primary is-link is-small expand"  >
    <span>Rèm Gỗ</span>
  </a>



		</div>
					</div>

	

	<div id="col-1527203100" class="col medium-4 small-12 large-2"  >
				<div class="col-inner"  >
			
			

<a href="https://remcuahn.com/danh-muc/rem-cuon/" target="_self" class="button primary is-link is-small expand"  >
    <span>Rèm Cuốn</span>
  </a>



		</div>
					</div>

	

	<div id="col-265189996" class="col medium-4 small-12 large-2"  >
				<div class="col-inner"  >
			
			

<a href="https://remcuahn.com/danh-muc/rem-la-doc/" target="_self" class="button primary is-link is-small expand"  >
    <span>Rèm Lá Dọc</span>
  </a>



		</div>
					</div>

	


<style>
#row-1015758727 > .col > .col-inner {
  padding: 15px 0px 0px 0px;
  background-color: rgb(255,255,255);
}
</style>
</div>

		</div>
					</div>

	

</div>

		</div>

		
<style>
#section_728579558 {
  padding-top: 30px;
  padding-bottom: 30px;
  background-color: rgb(255, 0, 0);
}
</style>
	</section>
	
	<section class="section" id="section_1003604939">
		<div class="bg section-bg fill bg-fill bg-loaded bg-loaded" >

			
			
			

		</div>

		<div class="section-content relative">
			

<div class="row" style="max-width:1680px" id="row-216405261">


	<div id="col-1203234718" class="col medium-12 small-12 large-4"  >
				<div class="col-inner"  >
			
			

<p><span style="font-size: 120%;">VỀ CHÚNG TÔI</span></p>
<p>CÔNG TY CỔ PHẦN XÂY DỰNG VÀ NỘI THẤT THANH NHÀN</p>
<p>– Số GPĐKKD: 0108464494 – Cấp ngày: 09 – 10 – 2018 || Tại sở kế hoạch đầu tư thành phố Hà Nội</p>
<p>– Địa chỉ trụ sở: LK-323,DV-14, Đất Dịch Vụ Hòa Bình, Phường Yên Nghĩa, Quận Hà Đông, Hà Nội. (<strong>Đối diện cổng Trường mầm non Lê Trọng Tấn</strong>)</p>
<p>– Điện thoại: 024 3201 2676</p>
<p>– Mobile: 083 836 9868 – 091 211 9901</p>
<p>– Email: quangr77@gmail.com</p>

		</div>
					</div>

	

	<div id="col-1401380562" class="col medium-12 small-12 large-5"  >
				<div class="col-inner"  >
			
			

<div class="row row-collapse"  id="row-1539890394">


	<div id="col-1861736951" class="col medium-6 small-12 large-6"  >
				<div class="col-inner"  >
			
			

<p><span style="font-size: 120%;">HỖ TRỢ KHÁCH HÀNG</span></p>
<ul>
<li><a href="https://remcuahn.com/chinh-sach-bao-mat/" rel="nofollow">Chính sách bảo mật thông tin cá nhân</a></li>
<li><a href="https://remcuahn.com/chinh-sach-bao-hanh/" rel="nofollow">Chính sách bảo hành</a></li>
<li><a href="https://remcuahn.com/chinh-sach-doi-hang/" rel="nofollow">Chính sách đổi hàng</a></li>
<li><a href="https://remcuahn.com/chinh-sach-van-chuyen/" rel="nofollow">Chính sách vận chuyển</a></li>
</ul>
	<div class="img has-hover x md-x lg-x y md-y lg-y" id="image_852037176">
								<div class="img-inner dark" >
									
					</div>
								
<style>
#image_852037176 {
  width: 100%;
}
</style>
	</div>
	

<p><a href="http://online.gov.vn/Home/WebDetails/73489" rel="nofollow"><noscript><img src="https://remcuahn.com/wp-content/uploads/2020/11/thong-bao-bo-cong-thuong.png" alt="Thông báo bộ công thương Rèm Thanh Nhàn" width="220" height="81" class="textwidget custom-html-widget"></noscript></a><a href="http://online.gov.vn/Home/WebDetails/73489" rel="nofollow"><img class="textwidget custom-html-widget alignnone" src="https://remcuahn.com/wp-content/uploads/2020/11/thong-bao-bo-cong-thuong.png" alt="Thông báo bộ công thương Rèm Thanh Nhàn" width="220" height="81" data-src="https://remcuahn.com/wp-content/uploads/2020/11/thong-bao-bo-cong-thuong.png" /></a></p>

		</div>
					</div>

	

	<div id="col-1059201613" class="col medium-6 small-12 large-6"  >
				<div class="col-inner"  >
			
			

<p><span style="font-size: 120%;">THÔNG TIN</span></p>
<ul>
<li><a href="https://remcuahn.com/gioi-thieu/" rel="nofollow">Giới thiệu</a></li>
<li><a href="https://remcuahn.com/tai-khoan/" rel="nofollow">Tài khoản</a></li>
<li><a href="https://remcuahn.com/mau-rem-cua-so-dep-bao-gia-nam-2020/">Mẫu rèm cửa sổ đẹp, Báo giá năm 2020</a></li>
<li><a href="https://remcuahn.com/manh-rem-cua/">Mành rèm cửa</a></li>
</ul>
	<div class="img has-hover x md-x lg-x y md-y lg-y" id="image_837361006">
								<div class="img-inner dark" >
			<img width="600" height="200" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20600%20200'%3E%3C/svg%3E" class="attachment-large size-large" alt="Thanh toán" data-lazy-srcset="https://remcuahn.com/wp-content/uploads/2021/08/thanh-toan.jpg 600w, https://remcuahn.com/wp-content/uploads/2021/08/thanh-toan-510x170.jpg 510w" data-lazy-sizes="(max-width: 600px) 100vw, 600px" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/08/thanh-toan.jpg" /><noscript><img width="600" height="200" src="https://remcuahn.com/wp-content/uploads/2021/08/thanh-toan.jpg" class="attachment-large size-large" alt="Thanh toán" srcset="https://remcuahn.com/wp-content/uploads/2021/08/thanh-toan.jpg 600w, https://remcuahn.com/wp-content/uploads/2021/08/thanh-toan-510x170.jpg 510w" sizes="(max-width: 600px) 100vw, 600px" /></noscript>						
					</div>
								
<style>
#image_837361006 {
  width: 100%;
}
</style>
	</div>
	


		</div>
					</div>

	

</div>

		</div>
					</div>

	

	<div id="col-402758121" class="col medium-12 small-12 large-3"  >
				<div class="col-inner"  >
			
			

<p><span style="font-size: 120%;">THEO DÕI CHÚNG TÔI</span></p>
<div class="social-icons follow-icons" style="font-size:110%"><a href="https://www.facebook.com/ManhRemThanhNhan/" target="_blank" data-label="Facebook" rel="noopener noreferrer nofollow" class="icon primary button circle facebook tooltip" title="Follow on Facebook" aria-label="Follow on Facebook"><i class="icon-facebook" ></i></a><a href="https://www.instagram.com/remthanhnhanvn/" target="_blank" rel="noopener noreferrer nofollow" data-label="Instagram" class="icon primary button circle  instagram tooltip" title="Follow on Instagram" aria-label="Follow on Instagram"><i class="icon-instagram" ></i></a><a href="https://twitter.com/remthanhnhanvn/" target="_blank" data-label="Twitter" rel="noopener noreferrer nofollow" class="icon primary button circle  twitter tooltip" title="Follow on Twitter" aria-label="Follow on Twitter"><i class="icon-twitter" ></i></a><a href="https://www.pinterest.com/remthanhnhanvn/" target="_blank" rel="noopener noreferrer nofollow"  data-label="Pinterest"  class="icon primary button circle  pinterest tooltip" title="Follow on Pinterest" aria-label="Follow on Pinterest"><i class="icon-pinterest" ></i></a><a href="https://www.linkedin.com/in/remthanhnhanvn/" target="_blank" rel="noopener noreferrer nofollow" data-label="LinkedIn" class="icon primary button circle  linkedin tooltip" title="Follow on LinkedIn" aria-label="Follow on LinkedIn"><i class="icon-linkedin" ></i></a><a href="https://www.youtube.com/channel/UC-7eesq6KpLBkfpxjcYhe6Q" target="_blank" rel="noopener noreferrer nofollow" data-label="YouTube" class="icon primary button circle  youtube tooltip" title="Follow on YouTube" aria-label="Follow on YouTube"><i class="icon-youtube" ></i></a></div>

<iframe loading="lazy" src="about:blank" width="365" height="150" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" data-rocket-lazyload="fitvidscompatible" data-lazy-src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FRemCuaDep.ThanhNhan%2F&#038;tabs=time&#038;width=365&#038;height=150&#038;small_header=false&#038;adapt_container_width=true&#038;hide_cover=false&#038;show_facepile=true&#038;appId=705097193446161"></iframe><noscript><iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FRemCuaDep.ThanhNhan%2F&tabs=time&width=365&height=150&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId=705097193446161" width="365" height="150" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"></iframe></noscript>
<p><span style="font-size: 110%;">ĐĂNG KÝ NHẬN BẢN TIN KHUYẾN MÃI</span></p>
<div role="form" class="wpcf7" id="wpcf7-f3250-o2" lang="vi" dir="ltr">
<div class="screen-reader-response"><p role="status" aria-live="polite" aria-atomic="true"></p> <ul></ul></div>
<form action="/#wpcf7-f3250-o2" method="post" class="wpcf7-form init" novalidate="novalidate" data-status="init">
<div style="display: none;">
<input type="hidden" name="_wpcf7" value="3250" />
<input type="hidden" name="_wpcf7_version" value="5.4.2" />
<input type="hidden" name="_wpcf7_locale" value="vi" />
<input type="hidden" name="_wpcf7_unit_tag" value="wpcf7-f3250-o2" />
<input type="hidden" name="_wpcf7_container_post" value="0" />
<input type="hidden" name="_wpcf7_posted_data_hash" value="" />
</div>
<div class="flex-row form-flat medium-flex-wrap">
<div class="flex-col flex-grow>
        <span class="wpcf7-form-control-wrap your-email"><input type="email" name="your-email" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-email wpcf7-validates-as-required wpcf7-validates-as-email" aria-required="true" aria-invalid="false" placeholder="Địa chỉ email (*)" /></span>
    </div>
<div class="flex-col ml-half">
        <input type="submit" value="Đăng ký" class="wpcf7-form-control wpcf7-submit button" />
    </div>
</div>
<div class="wpcf7-response-output" aria-hidden="true"></div></form></div>


		</div>
					</div>

	

</div>

		</div>

		
<style>
#section_1003604939 {
  padding-top: 30px;
  padding-bottom: 30px;
  background-color: rgb(231, 231, 231);
}
</style>
	</section>
	
<div class="absolute-footer dark medium-text-center text-center">
  <div class="container clearfix">

    
    <div class="footer-primary pull-left">
            <div class="copyright-footer">
        <span style="color: #ff0000;">©2015 - Thiết kế bởi - <strong><a href="https://remcuahn.com/">remcuahn.com<a></strong></span>
      </div>
          </div>
  </div>
</div>

</footer>

</div>

<div id="main-menu" class="mobile-sidebar no-scrollbar mfp-hide">
	<div class="sidebar-menu no-scrollbar ">
		<ul class="nav nav-sidebar nav-vertical nav-uppercase">
			<li class="header-search-form search-form html relative has-icon">
	<div class="header-search-form-wrapper">
		<div class="searchform-wrapper ux-search-box relative is-normal"><form role="search" method="get" class="searchform" action="https://remcuahn.com/">
	<div class="flex-row relative">
						<div class="flex-col flex-grow">
			<label class="screen-reader-text" for="woocommerce-product-search-field-1">Tìm kiếm:</label>
			<input type="search" id="woocommerce-product-search-field-1" class="search-field mb-0" placeholder="Tìm kiếm&hellip;" value="" name="s" />
			<input type="hidden" name="post_type" value="product" />
					</div>
		<div class="flex-col">
			<button type="submit" value="Tìm kiếm" class="ux-search-submit submit-button secondary button icon mb-0" aria-label="Submit">
				<i class="icon-search" ></i>			</button>
		</div>
	</div>
	<div class="live-search-results text-left z-top"></div>
</form>
</div>	</div>
</li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home current-menu-item page_item page-item-3229 current_page_item menu-item-3248"><a href="https://remcuahn.com/" aria-current="page">Trang Chủ</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-90"><a href="https://remcuahn.com/rem-cua/">Rèm Cửa</a>
<ul class="sub-menu nav-sidebar-ul children">
	<li id="menu-item-84" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-has-children menu-item-84"><a href="https://remcuahn.com/danh-muc/rem-vai/">Mẫu Rèm Vải</a>
	<ul class="sub-menu nav-sidebar-ul">
		<li id="menu-item-88" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-88"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-mot-mau/">Mẫu Rèm Vải Một Màu</a></li>
		<li id="menu-item-87" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-87"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-hoa-van/">Mẫu Rèm Vải Hoa Văn</a></li>
		<li id="menu-item-85" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-85"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-cao-cap/">Mẫu Rèm Vải Cao Cấp</a></li>
		<li id="menu-item-86" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-86"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-vai-gia-re/">Mẫu Rèm Vải Giá Rẻ</a></li>
	</ul>
</li>
	<li id="menu-item-82" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-82"><a href="https://remcuahn.com/danh-muc/rem-roman/">Mẫu Rèm Roman</a></li>
	<li id="menu-item-80" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-80"><a href="https://remcuahn.com/danh-muc/rem-go/">Rèm Gỗ &#8211; Mành Gỗ</a></li>
	<li id="menu-item-76" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-76"><a href="https://remcuahn.com/danh-muc/rem-cau-vong/">Mẫu Rèm Cầu Vồng</a></li>
	<li id="menu-item-77" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-77"><a href="https://remcuahn.com/danh-muc/rem-cuon/">Rèm Cuốn &#8211; Màn Cuốn</a></li>
	<li id="menu-item-79" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-79"><a href="https://remcuahn.com/danh-muc/rem-cuon-tranh/">Mẫu Rèm Cuốn Tranh</a></li>
	<li id="menu-item-81" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-81"><a href="https://remcuahn.com/danh-muc/rem-la-doc/">Mẫu Rèm Lá Dọc</a></li>
	<li id="menu-item-83" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-83"><a href="https://remcuahn.com/danh-muc/rem-sao-nhom/">Mẫu Rèm Sáo Nhôm</a></li>
	<li id="menu-item-89" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-89"><a href="https://remcuahn.com/danh-muc/rem-vai/rem-ngan-lanh-dieu-hoa/">Rèm Ngăn Lạnh Điều Hòa</a></li>
	<li id="menu-item-1490" class="menu-item menu-item-type-taxonomy menu-item-object-product_cat menu-item-1490"><a href="https://remcuahn.com/danh-muc/mau-rem-hat-go/">Mẫu Rèm Hạt Gỗ</a></li>
</ul>
</li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-has-children menu-item-33"><a href="https://remcuahn.com/tu-van-rem-cua/">Tư Vấn Rèm Cửa</a>
<ul class="sub-menu nav-sidebar-ul children">
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-41"><a href="https://remcuahn.com/tu-van-rem-cua/rem-roman/">Rèm Cửa Roman</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-42"><a href="https://remcuahn.com/tu-van-rem-cua/man-rem-vai-2-lop/">Màn Rèm Vải 2 Lớp</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-46"><a href="https://remcuahn.com/tu-van-rem-cua/rem-vai-mot-mau/">Rèm Vải Một Màu</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-43"><a href="https://remcuahn.com/tu-van-rem-cua/rem-cua-cao-cap/">Rèm Cửa Cao Cấp</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-44"><a href="https://remcuahn.com/tu-van-rem-cua/rem-dep-gia-re/">Rèm Đẹp Giá Rẻ</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-47"><a href="https://remcuahn.com/tu-van-rem-cua/rem-ngan-phong-dieu-hoa/">Rèm Ngăn Phòng Điều Hòa</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-37"><a href="https://remcuahn.com/tu-van-rem-cua/rem-cau-vong/">Rèm Cửa Cầu Vồng</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-39"><a href="https://remcuahn.com/tu-van-rem-cua/rem-go/">Rèm Sáo Gỗ</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-38"><a href="https://remcuahn.com/tu-van-rem-cua/rem-cuon/">Rèm Cửa Cuốn</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-40"><a href="https://remcuahn.com/tu-van-rem-cua/rem-la-doc/">Rèm Cửa Lá Dọc</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-36"><a href="https://remcuahn.com/tu-van-rem-cua/man-sao-nhom/">Màn Sáo Nhôm</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-2587"><a href="https://remcuahn.com/rem-hat-go-phong-thuy/">Rèm hạt gỗ phong thủy</a></li>
</ul>
</li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-has-children menu-item-32"><a href="https://remcuahn.com/tin-tuc/">Tin Tức</a>
<ul class="sub-menu nav-sidebar-ul children">
	<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-2086"><a href="https://remcuahn.com/mau-rem-cua-so-dep-bao-gia-nam-2020/">Rèm cửa sổ đẹp</a></li>
	<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-2328"><a href="https://remcuahn.com/mau-rem-roman-rem-xep-lop/">Mẫu rèm ROMAN</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-35"><a href="https://remcuahn.com/tin-tuc/khach-hang/">Khách Hàng</a></li>
	<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-34"><a href="https://remcuahn.com/tin-tuc/bao-gia/">Báo Giá</a></li>
</ul>
</li>
<li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1080"><a href="https://remcuahn.com/lien-he/">Liên Hệ</a></li>
<li class="html header-social-icons ml-0">
	<div class="social-icons follow-icons" ><a href="https://www.facebook.com/ManhRemThanhNhan/" target="_blank" data-label="Facebook" rel="noopener noreferrer nofollow" class="icon plain facebook tooltip" title="Follow on Facebook" aria-label="Follow on Facebook"><i class="icon-facebook" ></i></a><a href="https://www.instagram.com/remthanhnhanvn/" target="_blank" rel="noopener noreferrer nofollow" data-label="Instagram" class="icon plain  instagram tooltip" title="Follow on Instagram" aria-label="Follow on Instagram"><i class="icon-instagram" ></i></a><a href="https://www.tiktok.com/@remthanhnhanhn/" target="_blank" rel="noopener noreferrer nofollow" data-label="TikTok" class="icon plain tiktok tooltip" title="Follow on TikTok" aria-label="Follow on TikTok"><i class="icon-tiktok" ></i></a><a href="https://twitter.com/remthanhnhanvn/" target="_blank" data-label="Twitter" rel="noopener noreferrer nofollow" class="icon plain  twitter tooltip" title="Follow on Twitter" aria-label="Follow on Twitter"><i class="icon-twitter" ></i></a><a href="mailto:quangr77@gmail.com" data-label="E-mail" rel="nofollow" class="icon plain  email tooltip" title="Send us an email" aria-label="Send us an email"><i class="icon-envelop" ></i></a><a href="https://www.pinterest.com/remthanhnhanvn/" target="_blank" rel="noopener noreferrer nofollow"  data-label="Pinterest"  class="icon plain  pinterest tooltip" title="Follow on Pinterest" aria-label="Follow on Pinterest"><i class="icon-pinterest" ></i></a><a href="https://www.linkedin.com/in/remthanhnhanvn/" target="_blank" rel="noopener noreferrer nofollow" data-label="LinkedIn" class="icon plain  linkedin tooltip" title="Follow on LinkedIn" aria-label="Follow on LinkedIn"><i class="icon-linkedin" ></i></a><a href="https://www.youtube.com/channel/UC-7eesq6KpLBkfpxjcYhe6Q" target="_blank" rel="noopener noreferrer nofollow" data-label="YouTube" class="icon plain  youtube tooltip" title="Follow on YouTube" aria-label="Follow on YouTube"><i class="icon-youtube" ></i></a><a href="https://www.flickr.com/photos/remthanhnhanvn/" target="_blank" rel="noopener noreferrer nofollow" data-label="Flickr" class="icon plain  flickr tooltip" title="Flickr" aria-label="Flickr"><i class="icon-flickr" ></i></a><a href="https://vk.com/remthanhnhan" target="_blank" data-label="VKontakte" rel="noopener noreferrer nofollow" class="icon plain vk tooltip" title="Follow on VKontakte" aria-label="Follow on VKontakte"><i class="icon-vk" ></i></a><a href="https://t.me/remthanhnhan" target="_blank" data-label="Telegram" rel="noopener noreferrer nofollow" class="icon plain telegram tooltip" title="Follow on Telegram" aria-label="Follow on Telegram"><i class="icon-telegram" ></i></a></div></li>		</ul>
	</div>
</div>
<div class="hotline-phone-ring-wrap">
	<div class="hotline-phone-ring">
		<div class="hotline-phone-ring-circle"></div>
		<div class="hotline-phone-ring-circle-fill"></div>
		<div class="hotline-phone-ring-img-circle">
		<a href="Tel:0838369868" class="pps-btn-img">
			<img src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2040%200'%3E%3C/svg%3E" alt="Gọi điện thoại" width="40" data-lazy-src="https://remcuahn.com/wp-content/uploads/2021/09/icon-call.png"><noscript><img src="https://remcuahn.com/wp-content/uploads/2021/09/icon-call.png" alt="Gọi điện thoại" width="40"></noscript>
		</a>
		</div>
	</div>
	<div class="hotline-bar">
		<a href="Tel: 0838369868">
			<span class="text-hotline">083 8369 868</span>
		</a>
	</div>
</div>
    <div id="login-form-popup" class="lightbox-content mfp-hide">
            <div class="woocommerce-notices-wrapper"></div>
<div class="account-container lightbox-inner">

	
	<div class="col2-set row row-divided row-large" id="customer_login">

		<div class="col-1 large-6 col pb-0">

			
			<div class="account-login-inner">

				<h3 class="uppercase">Đăng nhập</h3>

				<form class="woocommerce-form woocommerce-form-login login" method="post">

					
					<p class="woocommerce-form-row woocommerce-form-row--wide form-row form-row-wide">
						<label for="username">Tên tài khoản hoặc địa chỉ email&nbsp;<span class="required">*</span></label>
						<input type="text" class="woocommerce-Input woocommerce-Input--text input-text" name="username" id="username" autocomplete="username" value="" />					</p>
					<p class="woocommerce-form-row woocommerce-form-row--wide form-row form-row-wide">
						<label for="password">Mật khẩu&nbsp;<span class="required">*</span></label>
						<input class="woocommerce-Input woocommerce-Input--text input-text" type="password" name="password" id="password" autocomplete="current-password" />
					</p>

					
					<p class="form-row">
						<label class="woocommerce-form__label woocommerce-form__label-for-checkbox woocommerce-form-login__rememberme">
							<input class="woocommerce-form__input woocommerce-form__input-checkbox" name="rememberme" type="checkbox" id="rememberme" value="forever" /> <span>Ghi nhớ mật khẩu</span>
						</label>
						<input type="hidden" id="woocommerce-login-nonce" name="woocommerce-login-nonce" value="79c43ea6e3" /><input type="hidden" name="_wp_http_referer" value="/" />						<button type="submit" class="woocommerce-button button woocommerce-form-login__submit" name="login" value="Đăng nhập">Đăng nhập</button>
					</p>
					<p class="woocommerce-LostPassword lost_password">
						<a href="https://remcuahn.com/tai-khoan/lost-password/">Quên mật khẩu?</a>
					</p>

					
				</form>
			</div>

			
		</div>

		<div class="col-2 large-6 col pb-0">

			<div class="account-register-inner">

				<h3 class="uppercase">Đăng ký</h3>

				<form method="post" class="woocommerce-form woocommerce-form-register register"  >

					
					
					<p class="woocommerce-form-row woocommerce-form-row--wide form-row form-row-wide">
						<label for="reg_email">Địa chỉ email&nbsp;<span class="required">*</span></label>
						<input type="email" class="woocommerce-Input woocommerce-Input--text input-text" name="email" id="reg_email" autocomplete="email" value="" />					</p>

					
						<p>Một mật khẩu sẽ được gửi đến địa chỉ email của bạn.</p>

					
					<div class="woocommerce-privacy-policy-text"><p>Thông tin cá nhân của bạn sẽ được sử dụng để tăng trải nghiệm sử dụng website, quản lý truy cập vào tài khoản của bạn, và cho các mục đích cụ thể khác được mô tả trong <a href="https://remcuahn.com/chinh-sach-bao-mat/" class="woocommerce-privacy-policy-link" target="_blank">chính sách riêng tư</a>.</p>
</div>
					<p class="woocommerce-form-row form-row">
						<input type="hidden" id="woocommerce-register-nonce" name="woocommerce-register-nonce" value="76288becbe" /><input type="hidden" name="_wp_http_referer" value="/" />						<button type="submit" class="woocommerce-Button woocommerce-button button woocommerce-form-register__submit" name="register" value="Đăng ký">Đăng ký</button>
					</p>

					
				</form>

			</div>

		</div>

	</div>

</div>

          </div>
  <div class="mbwph-fbc "><div id="fb-root"></div> </div>
						<script type="rocketlazyloadscript">
						window.fbAsyncInit = function() {
						FB.init({
							xfbml            : true,
							version          : "v8.0"
						});
						};
						(function(d, s, id) {
						var js, fjs = d.getElementsByTagName(s)[0];
						if (d.getElementById(id)) return;
						js = d.createElement(s); js.id = id;
						js.src = "https://connect.facebook.net/vi_VN/sdk/xfbml.customerchat.js";
						fjs.parentNode.insertBefore(js, fjs);
					}(document, "script", "facebook-jssdk"));</script><div class="fb-customerchat"
						attribution=setup_tool
						page_id=""
						theme_color=""
						logged_in_greeting=""
						logged_out_greeting=""
						alignment="left">
					</div>	<script type="rocketlazyloadscript" data-rocket-type="text/javascript">
		(function () {
			var c = document.body.className;
			c = c.replace(/woocommerce-no-js/, 'woocommerce-js');
			document.body.className = c;
		})();
	</script>
	
<script type="rocketlazyloadscript" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-includes/js/dist/vendor/wp-polyfill.min.js?ver=7.4.4' id='wp-polyfill-js'></script>
<script type="rocketlazyloadscript" data-rocket-type='text/javascript' id='wp-polyfill-js-after'>
( 'fetch' in window ) || document.write( '<script src="https://remcuahn.com/wp-includes/js/dist/vendor/wp-polyfill-fetch.min.js?ver=3.0.0" defer></scr' + 'ipt>' );( document.contains ) || document.write( '<script src="https://remcuahn.com/wp-includes/js/dist/vendor/wp-polyfill-node-contains.min.js?ver=3.42.0" defer></scr' + 'ipt>' );( window.DOMRect ) || document.write( '<script src="https://remcuahn.com/wp-includes/js/dist/vendor/wp-polyfill-dom-rect.min.js?ver=3.42.0" defer></scr' + 'ipt>' );( window.URL && window.URL.prototype && window.URLSearchParams ) || document.write( '<script src="https://remcuahn.com/wp-includes/js/dist/vendor/wp-polyfill-url.min.js?ver=3.6.4" defer></scr' + 'ipt>' );( window.FormData && window.FormData.prototype.keys ) || document.write( '<script src="https://remcuahn.com/wp-includes/js/dist/vendor/wp-polyfill-formdata.min.js?ver=3.0.12" defer></scr' + 'ipt>' );( Element.prototype.matches && Element.prototype.closest ) || document.write( '<script src="https://remcuahn.com/wp-includes/js/dist/vendor/wp-polyfill-element-closest.min.js?ver=2.0.2" defer></scr' + 'ipt>' );( 'objectFit' in document.documentElement.style ) || document.write( '<script src="https://remcuahn.com/wp-includes/js/dist/vendor/wp-polyfill-object-fit.min.js?ver=2.3.4" defer></scr' + 'ipt>' );
</script>
<script type='text/javascript' id='contact-form-7-js-extra'>
/* <![CDATA[ */
var wpcf7 = {"api":{"root":"https:\/\/remcuahn.com\/wp-json\/","namespace":"contact-form-7\/v1"},"cached":"1"};
/* ]]> */
</script>
<script type="rocketlazyloadscript" data-minify="1" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-content/cache/min/1/wp-content/plugins/contact-form-7/includes/js/index.js?ver=1631963618' id='contact-form-7-js' defer></script>
<script type="rocketlazyloadscript" data-rocket-type='text/javascript' id='rocket-browser-checker-js-after'>
"use strict";var _createClass=function(){function defineProperties(target,props){for(var i=0;i<props.length;i++){var descriptor=props[i];descriptor.enumerable=descriptor.enumerable||!1,descriptor.configurable=!0,"value"in descriptor&&(descriptor.writable=!0),Object.defineProperty(target,descriptor.key,descriptor)}}return function(Constructor,protoProps,staticProps){return protoProps&&defineProperties(Constructor.prototype,protoProps),staticProps&&defineProperties(Constructor,staticProps),Constructor}}();function _classCallCheck(instance,Constructor){if(!(instance instanceof Constructor))throw new TypeError("Cannot call a class as a function")}var RocketBrowserCompatibilityChecker=function(){function RocketBrowserCompatibilityChecker(options){_classCallCheck(this,RocketBrowserCompatibilityChecker),this.passiveSupported=!1,this._checkPassiveOption(this),this.options=!!this.passiveSupported&&options}return _createClass(RocketBrowserCompatibilityChecker,[{key:"_checkPassiveOption",value:function(self){try{var options={get passive(){return!(self.passiveSupported=!0)}};window.addEventListener("test",null,options),window.removeEventListener("test",null,options)}catch(err){self.passiveSupported=!1}}},{key:"initRequestIdleCallback",value:function(){!1 in window&&(window.requestIdleCallback=function(cb){var start=Date.now();return setTimeout(function(){cb({didTimeout:!1,timeRemaining:function(){return Math.max(0,50-(Date.now()-start))}})},1)}),!1 in window&&(window.cancelIdleCallback=function(id){return clearTimeout(id)})}},{key:"isDataSaverModeOn",value:function(){return"connection"in navigator&&!0===navigator.connection.saveData}},{key:"supportsLinkPrefetch",value:function(){var elem=document.createElement("link");return elem.relList&&elem.relList.supports&&elem.relList.supports("prefetch")&&window.IntersectionObserver&&"isIntersecting"in IntersectionObserverEntry.prototype}},{key:"isSlowConnection",value:function(){return"connection"in navigator&&"effectiveType"in navigator.connection&&("2g"===navigator.connection.effectiveType||"slow-2g"===navigator.connection.effectiveType)}}]),RocketBrowserCompatibilityChecker}();
</script>
<script type='text/javascript' id='rocket-preload-links-js-extra'>
/* <![CDATA[ */
var RocketPreloadLinksConfig = {"excludeUris":"\/wp-admin\/|\/gio-hang\/|\/thanh-toan\/|\/tai-khoan\/|\/(.+\/)?feed\/?.+\/?|\/(?:.+\/)?embed\/|\/thanh-toan\/|\/gio-hang\/|\/tai-khoan\/|\/wc-api\/v(.*)|\/(index\\.php\/)?wp\\-json(\/.*|$)|\/wp-admin\/|\/logout\/|\/wp-login.php","usesTrailingSlash":"1","imageExt":"jpg|jpeg|gif|png|tiff|bmp|webp|avif","fileExt":"jpg|jpeg|gif|png|tiff|bmp|webp|avif|php|pdf|html|htm","siteUrl":"https:\/\/remcuahn.com","onHoverDelay":"100","rateThrottle":"3"};
/* ]]> */
</script>
<script type="rocketlazyloadscript" data-rocket-type='text/javascript' id='rocket-preload-links-js-after'>
(function() {
"use strict";var r="function"==typeof Symbol&&"symbol"==typeof Symbol.iterator?function(e){return typeof e}:function(e){return e&&"function"==typeof Symbol&&e.constructor===Symbol&&e!==Symbol.prototype?"symbol":typeof e},e=function(){function i(e,t){for(var n=0;n<t.length;n++){var i=t[n];i.enumerable=i.enumerable||!1,i.configurable=!0,"value"in i&&(i.writable=!0),Object.defineProperty(e,i.key,i)}}return function(e,t,n){return t&&i(e.prototype,t),n&&i(e,n),e}}();function i(e,t){if(!(e instanceof t))throw new TypeError("Cannot call a class as a function")}var t=function(){function n(e,t){i(this,n),this.browser=e,this.config=t,this.options=this.browser.options,this.prefetched=new Set,this.eventTime=null,this.threshold=1111,this.numOnHover=0}return e(n,[{key:"init",value:function(){!this.browser.supportsLinkPrefetch()||this.browser.isDataSaverModeOn()||this.browser.isSlowConnection()||(this.regex={excludeUris:RegExp(this.config.excludeUris,"i"),images:RegExp(".("+this.config.imageExt+")$","i"),fileExt:RegExp(".("+this.config.fileExt+")$","i")},this._initListeners(this))}},{key:"_initListeners",value:function(e){-1<this.config.onHoverDelay&&document.addEventListener("mouseover",e.listener.bind(e),e.listenerOptions),document.addEventListener("mousedown",e.listener.bind(e),e.listenerOptions),document.addEventListener("touchstart",e.listener.bind(e),e.listenerOptions)}},{key:"listener",value:function(e){var t=e.target.closest("a"),n=this._prepareUrl(t);if(null!==n)switch(e.type){case"mousedown":case"touchstart":this._addPrefetchLink(n);break;case"mouseover":this._earlyPrefetch(t,n,"mouseout")}}},{key:"_earlyPrefetch",value:function(t,e,n){var i=this,r=setTimeout(function(){if(r=null,0===i.numOnHover)setTimeout(function(){return i.numOnHover=0},1e3);else if(i.numOnHover>i.config.rateThrottle)return;i.numOnHover++,i._addPrefetchLink(e)},this.config.onHoverDelay);t.addEventListener(n,function e(){t.removeEventListener(n,e,{passive:!0}),null!==r&&(clearTimeout(r),r=null)},{passive:!0})}},{key:"_addPrefetchLink",value:function(i){return this.prefetched.add(i.href),new Promise(function(e,t){var n=document.createElement("link");n.rel="prefetch",n.href=i.href,n.onload=e,n.onerror=t,document.head.appendChild(n)}).catch(function(){})}},{key:"_prepareUrl",value:function(e){if(null===e||"object"!==(void 0===e?"undefined":r(e))||!1 in e||-1===["http:","https:"].indexOf(e.protocol))return null;var t=e.href.substring(0,this.config.siteUrl.length),n=this._getPathname(e.href,t),i={original:e.href,protocol:e.protocol,origin:t,pathname:n,href:t+n};return this._isLinkOk(i)?i:null}},{key:"_getPathname",value:function(e,t){var n=t?e.substring(this.config.siteUrl.length):e;return n.startsWith("/")||(n="/"+n),this._shouldAddTrailingSlash(n)?n+"/":n}},{key:"_shouldAddTrailingSlash",value:function(e){return this.config.usesTrailingSlash&&!e.endsWith("/")&&!this.regex.fileExt.test(e)}},{key:"_isLinkOk",value:function(e){return null!==e&&"object"===(void 0===e?"undefined":r(e))&&(!this.prefetched.has(e.href)&&e.origin===this.config.siteUrl&&-1===e.href.indexOf("?")&&-1===e.href.indexOf("#")&&!this.regex.excludeUris.test(e.href)&&!this.regex.images.test(e.href))}}],[{key:"run",value:function(){"undefined"!=typeof RocketPreloadLinksConfig&&new n(new RocketBrowserCompatibilityChecker({capture:!0,passive:!0}),RocketPreloadLinksConfig).init()}}]),n}();t.run();
}());
</script>
<script type="rocketlazyloadscript" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-includes/js/hoverIntent.min.js?ver=1.8.1' id='hoverIntent-js' defer></script>
<script type='text/javascript' id='flatsome-js-js-extra'>
/* <![CDATA[ */
var flatsomeVars = {"ajaxurl":"https:\/\/remcuahn.com\/wp-admin\/admin-ajax.php","rtl":"","sticky_height":"70","assets_url":"https:\/\/remcuahn.com\/wp-content\/themes\/flatsome\/assets\/js\/","lightbox":{"close_markup":"<button title=\"%title%\" type=\"button\" class=\"mfp-close\"><svg xmlns=\"http:\/\/www.w3.org\/2000\/svg\" width=\"28\" height=\"28\" viewBox=\"0 0 24 24\" fill=\"none\" stroke=\"currentColor\" stroke-width=\"2\" stroke-linecap=\"round\" stroke-linejoin=\"round\" class=\"feather feather-x\"><line x1=\"18\" y1=\"6\" x2=\"6\" y2=\"18\"><\/line><line x1=\"6\" y1=\"6\" x2=\"18\" y2=\"18\"><\/line><\/svg><\/button>","close_btn_inside":false},"user":{"can_edit_pages":false},"i18n":{"mainMenu":"Main Menu"},"options":{"cookie_notice_version":"1","swatches_layout":false,"swatches_box_select_event":false,"swatches_box_behavior_selected":false,"swatches_box_update_urls":"1","swatches_box_reset":false,"swatches_box_reset_extent":false,"swatches_box_reset_time":300,"search_result_latency":"0"},"is_mini_cart_reveal":""};
/* ]]> */
</script>
<script type="rocketlazyloadscript" data-minify="1" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-content/cache/min/1/wp-content/themes/flatsome/assets/js/flatsome.js?ver=1631963619' id='flatsome-js-js' defer></script>
<script type="rocketlazyloadscript" data-minify="1" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-content/cache/min/1/wp-content/themes/flatsome/inc/integrations/wp-rocket/flatsome-wp-rocket.js?ver=1631963619' id='flatsome-wp-rocket-js' defer></script>
<script type="rocketlazyloadscript" data-minify="1" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-content/cache/min/1/wp-content/themes/flatsome/inc/extensions/flatsome-live-search/flatsome-live-search.js?ver=1631963619' id='flatsome-live-search-js' defer></script>
<script type="rocketlazyloadscript" data-minify="1" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-content/cache/min/1/wp-content/themes/flatsome/assets/js/woocommerce.js?ver=1631963619' id='flatsome-theme-woocommerce-js-js' defer></script>
<!--[if IE]>
<script type='text/javascript' src='https://cdn.jsdelivr.net/gh/nuxodin/ie11CustomProperties@4.0.1/ie11CustomProperties.min.js?ver=4.0.1' id='css-vars-polyfill-js'></script>
<![endif]-->
<script type="rocketlazyloadscript" data-rocket-type='text/javascript' src='https://remcuahn.com/wp-content/themes/flatsome/assets/libs/packery.pkgd.min.js?ver=3.14.2' id='flatsome-masonry-js-js' defer></script>
			<script type="rocketlazyloadscript" data-rocket-type="text/javascript" id="wpsp-script-frontend"></script>
			<!-- Load Facebook SDK for JavaScript -->
<div id="fb-root"></div>
    <script type="rocketlazyloadscript">
      window.fbAsyncInit = function() {
        FB.init({
          xfbml            : true,
          version          : 'v11.0'
        });
      };

      (function(d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        if (d.getElementById(id)) return;
        js = d.createElement(s); js.id = id;
        js.src = 'https://connect.facebook.net/vi_VN/sdk/xfbml.customerchat.js';
        fjs.parentNode.insertBefore(js, fjs);
      }(document, 'script', 'facebook-jssdk'));
    </script>

<!-- Your customer chat code -->
<div class="fb-customerchat"
  attribution=setup_tool
  page_id="1266512393467498">
</div><script>window.lazyLoadOptions={elements_selector:"img[data-lazy-src],.rocket-lazyload,iframe[data-lazy-src]",data_src:"lazy-src",data_srcset:"lazy-srcset",data_sizes:"lazy-sizes",class_loading:"lazyloading",class_loaded:"lazyloaded",threshold:300,callback_loaded:function(element){if(element.tagName==="IFRAME"&&element.dataset.rocketLazyload=="fitvidscompatible"){if(element.classList.contains("lazyloaded")){if(typeof window.jQuery!="undefined"){if(jQuery.fn.fitVids){jQuery(element).parent().fitVids()}}}}}};window.addEventListener('LazyLoad::Initialized',function(e){var lazyLoadInstance=e.detail.instance;if(window.MutationObserver){var observer=new MutationObserver(function(mutations){var image_count=0;var iframe_count=0;var rocketlazy_count=0;mutations.forEach(function(mutation){for(i=0;i<mutation.addedNodes.length;i++){if(typeof mutation.addedNodes[i].getElementsByTagName!=='function'){continue}
if(typeof mutation.addedNodes[i].getElementsByClassName!=='function'){continue}
images=mutation.addedNodes[i].getElementsByTagName('img');is_image=mutation.addedNodes[i].tagName=="IMG";iframes=mutation.addedNodes[i].getElementsByTagName('iframe');is_iframe=mutation.addedNodes[i].tagName=="IFRAME";rocket_lazy=mutation.addedNodes[i].getElementsByClassName('rocket-lazyload');image_count+=images.length;iframe_count+=iframes.length;rocketlazy_count+=rocket_lazy.length;if(is_image){image_count+=1}
if(is_iframe){iframe_count+=1}}});if(image_count>0||iframe_count>0||rocketlazy_count>0){lazyLoadInstance.update()}});var b=document.getElementsByTagName("body")[0];var config={childList:!0,subtree:!0};observer.observe(b,config)}},!1)</script><script data-no-minify="1" async src="https://remcuahn.com/wp-content/plugins/wp-rocket/assets/js/lazyload/16.1/lazyload.min.js"></script>
<script type="rocketlazyloadscript">"use strict";var wprRemoveCPCSS=function wprRemoveCPCSS(){var elem;document.querySelector('link[data-rocket-async="style"][rel="preload"]')?setTimeout(wprRemoveCPCSS,200):(elem=document.getElementById("rocket-critical-css"))&&"remove"in elem&&elem.remove()};window.addEventListener?window.addEventListener("load",wprRemoveCPCSS):window.attachEvent&&window.attachEvent("onload",wprRemoveCPCSS);</script><noscript><link rel="stylesheet" href="https://remcuahn.com/wp-content/cache/min/1/04fa7a1cb8a91438ab32cb19ec945497.css" media="all" data-minify="1" /><link rel='stylesheet' id='flatsome-googlefonts-css'  href='//fonts.googleapis.com/css?family=Lato%3Aregular%2C700%2C400%2C700%7CDancing+Script%3Aregular%2C400&#038;display=swap&#038;ver=3.9' type='text/css' media='all' /></noscript></body>
</html>

<!-- This website is like a Rocket, isn't it? Performance optimized by WP Rocket. Learn more: https://wp-rocket.me - Debug: cached@1631967862 -->
