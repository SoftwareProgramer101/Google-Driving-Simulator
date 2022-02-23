<html prefix="og: http://ogp.me/ns#"><head>
	<meta charset="utf-8">
	<title>Driving Simulator on Google Maps - Frame Synthesis</title>

	<meta name="viewport" content="width=device-width,maximum-scale=1.0">
	
<link rel="shortcut icon" href="/favicon.ico">

<link rel="apple-touch-icon-precomposed" href="/icons/Icon-152.png">

<meta name="msapplication-TileColor" content="#FFFFFF">
<meta name="msapplication-TileImage" content="/icons/favicon-144.png">

	<link rel="alternate" type="application/rss+xml" title="Frame Synthesis" href="/blog/index.xml">

    <meta name="description" content="You can drive vehicles on Google Maps. You can drive safely, ignore roads, park, race on a circuit, and travel around the world. You can play in any way you want!">




    
        
    


<link rel="image_src" href="https://framesynthesis.com/assets/images/thumbnails/drivingsimulatorgm.jpg">


<meta property="og:title" content="Driving Simulator on Google Maps">
<meta property="og:type" content="article">
<meta property="og:url" content="https://framesynthesis.com/drivingsimulator/maps/">
<meta property="og:image" content="https://framesynthesis.com/assets/images/thumbnails/drivingsimulatorgm.jpg">
<meta property="og:site_name" content="Frame Synthesis">
<meta property="og:description" content="You can drive vehicles on Google Maps. You can drive safely, ignore roads, park, race on a circuit, and travel around the world. You can play in any way you want!">



<meta name="twitter:card" content="summary">
<meta name="twitter:image" content="https://framesynthesis.com/assets/images/thumbnails/drivingsimulatorgm.jpg">

<meta name="twitter:site" content="@korinVR_en">
<meta name="twitter:description" content="You can drive vehicles on Google Maps. You can drive safely, ignore roads, park, race on a circuit, and travel around the world. You can play in any way you want!">
<meta name="twitter:title" content="Driving Simulator on Google Maps">

<meta property="fb:admins" content="100000020423203">
<meta property="fb:app_id" content="711283445557703">

    
	<style>
.aspect-square {
	aspect-ratio: 1/1;
}

.aspect-16-9 {
	aspect-ratio: 16/9;
}

.aspect-4-3 {
	aspect-ratio: 4/3;
}
</style>

<style>
 
.adsense300x250 {
	width: 300px;
	height: 250px;
	background-color: #EEE;
}

.adsense336x280 {
	width: 336px;
	height: 280px;
	background-color: #EEE;
}

.adsense728x90 {
	width: 728px;
	height: 90px;
	background-color: #EEE;
}

.adsense160x600 {
	width: 160px;
	height: 600px;
	background-color: #EEE
}

.adsense320x50 {
	width: 320px;
	height: 50px;
	background-color: #EEE
}

.adsense468x60 {
	width: 468px;
	height: 60px;
	background-color: #EEE
}

.adsense_horizontal {
	width: 728px;
	height: 90px;

	margin: 30px auto;
}

@media (max-width: 750px) {
	.adsense_horizontal {
		width: 320px;
		height: 50px;
	}
}
</style>

<style>
header {
	padding: 30px 0;

	overflow: hidden;
	height: 40px;
}

	header .logo {
		float: left;

		width: 272px;
		height: 45px;

		background-image: url(/images/logo.png);
		background-size: 100%;
	}

header nav {
	float: right;
}

	header nav ul {
		margin: 0;
		padding: 0;
		float: left;
	}

	header nav li {
		margin: 0;
		padding: 0;
		list-style-type: none;
		display: inline-block;

		border-right: 1px solid #EEE;
	}

	header nav li:first-child {
		border-left: 1px solid #EEE;
	}

	header nav a {
		display: block;
		padding: 8px 15px;

		color: #333;
		text-decoration: none;
		font-size: 80%;
	}

	header nav a:hover {
		background-color: #F0F4F0;
	}

@media (max-width: 1050px) {
	header {
		margin-bottom: 0;
	}

	header .logo {
		width: calc(272px * 0.8);
		height: calc(45px * 0.8);
	}

	header nav {
		display: none;
	}
}
</style>


<style>
#mobile-menu, #mobile-menu-button {
	display: none;
}

@media (max-width: 1050px) {
	#mobile-menu, #mobile-menu-button {
		display: block;
	}

	#mobile-menu-button {
		float: right;
		width: 36px;
		height: 36px;

		cursor: pointer;

		-webkit-user-select: none;
		-webkit-tap-highlight-color: rgba(0, 0, 0, 0);

		 

		background-image: url(/images/mobile_menu_button.svg);
		background-size: 100%;

		position: relative;
		z-index: 100;
	}

	#mobile-menu-button:after {
		position: absolute;
		content: "";
		top: -10px;
		left: -10px;
		right: -10px;
		bottom: -10px;
	}

	#pc-menu {
		display: none;
	}

	#mobile-menu {
		position: absolute;
		z-index: 100;

		width: 100%;
		background-color: #FFF;

		 

		transition: transform .2s ease-out;
		transition: -webkit-transform .2s ease-out;

		transform-origin: 50% 0;
		-webkit-transform-origin: 50% 0;
	}

	#mobile-menu.hidden {
		transform: rotateX(90deg);
		-webkit-transform: rotateX(90deg);
	}

	#mobile-menu.visible {
		transform: rotateX(0deg);
		-webkit-transform: rotateX(0deg);
	}

	 
	#mobile-menu ul {
		margin: 0;
		padding: 0;
	}

	#mobile-menu li {
		list-style: none;
		padding: 10px 48px;

		border-bottom: 1px solid #CCC;
	}

	#mobile-menu li:first-child {
		border-top: 1px solid #CCC;
	}
}
</style>


<style>

html {
	overflow-y: scroll;
}

body {
	margin: 0;

	font-family: 'Helvetica-Light', Arial, Meiryo, sans-serif;
	line-height: 1.7;
	 

	 
	-webkit-text-size-adjust: none;

	background-color: #FFF;
	color: #333;
}

h1, h2 {
	line-height: 1.3;
}

a {
	transition: color 100ms ease-in-out;
	color: #009999;
}

a:hover {
	color: #00CCCC;
}

img {
	 
	max-width: 100%;
	 
	border: 0;
}

footer {
	margin: 40px 0;
}

.container {
	max-width: 1000px;
	margin: 0 auto;
	padding: 0 15px;
}

.container-800 {
	max-width: 800px;
	margin: 0 auto;
	padding: 0 15px;
}

.container-728 {
	max-width: 728px;
	margin: 0 auto;
	padding: 0 15px;
}

.container-600 {
	max-width: 600px;
	margin: 0 auto;
	padding: 0 15px;
}

.gamecontainer {
	padding: 0;

	 
	touch-action: none;
}

.notsupported {
	background-color: #FFC;

	width: 100%;
	height: 100%;

	padding: 1em;
	box-sizing: border-box;
	-webkit-box-sizing: border-box;
}

.attention {
	padding: 0 20px;
	border:1px solid #CCC;
	border-radius:5px;
	background-color: #FFC;
}

.center-block {
	display: block;
	margin-left: auto;
	margin-right: auto;
}

table {
	width: 100%;
	border-collapse: collapse;
}

td {
	padding: 5px;
}
td:first-child
{
	white-space: nowrap;
}
tr:nth-child(odd)
{
	background-color: #EEE;
}

.twitter-timeline {
	margin: 20px 0;
}

@media (max-width: 600px) {
	.twitter-timeline {
		height: 300px;
	}

	table {
		width: 100%;
	}
}

.sns-buttons {
	margin: 10px auto;
	height: 24px;
	position: relative;
	overflow: hidden;
}

.sns-button {
	position: absolute;
}

 
.fb-like > span {
	vertical-align: top !important;
}

.entry {
	overflow: auto;
	margin: 20px 0;
}

	.entry > .left {
		float: left;
		width: 60%;
	}

		.entry > .left > h2 {
			margin-top: 0;
		}

	.entry > .right {
		float: right;
	}

		.entry > .right img {
			width: 250px;
		}

@media (max-width: 750px) {
	.entry > .left {
		float: none;
		width: 100%;
	}
	.entry > .right {
		float: none;
		width: 100%;
	}
}

</style>

	
	
	
<style type="text/css"></style><meta http-equiv="origin-trial" content="AxujKG9INjsZ8/gUq8+dTruNvk7RjZQ1oFhhgQbcTJKDnZfbzSTE81wvC2Hzaf3TW4avA76LTZEMdiedF1vIbA4AAABueyJvcmlnaW4iOiJodHRwczovL2ltYXNkay5nb29nbGVhcGlzLmNvbTo0NDMiLCJmZWF0dXJlIjoiVHJ1c3RUb2tlbnMiLCJleHBpcnkiOjE2NTI3NzQ0MDAsImlzVGhpcmRQYXJ0eSI6dHJ1ZX0="><meta http-equiv="origin-trial" content="Azuce85ORtSnWe1MZDTv68qpaW3iHyfL9YbLRy0cwcCZwVnePnOmkUJlG8HGikmOwhZU22dElCcfrfX2HhrBPAkAAAB7eyJvcmlnaW4iOiJodHRwczovL2RvdWJsZWNsaWNrLm5ldDo0NDMiLCJmZWF0dXJlIjoiVHJ1c3RUb2tlbnMiLCJleHBpcnkiOjE2NTI3NzQ0MDAsImlzU3ViZG9tYWluIjp0cnVlLCJpc1RoaXJkUGFydHkiOnRydWV9"><meta http-equiv="origin-trial" content="A16nvcdeoOAqrJcmjLRpl1I6f3McDD8EfofAYTt/P/H4/AWwB99nxiPp6kA0fXoiZav908Z8etuL16laFPUdfQsAAACBeyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXRhZ3NlcnZpY2VzLmNvbTo0NDMiLCJmZWF0dXJlIjoiVHJ1c3RUb2tlbnMiLCJleHBpcnkiOjE2NTI3NzQ0MDAsImlzU3ViZG9tYWluIjp0cnVlLCJpc1RoaXJkUGFydHkiOnRydWV9"><meta http-equiv="origin-trial" content="AxBHdr0J44vFBQtZUqX9sjiqf5yWZ/OcHRcRMN3H9TH+t90V/j3ENW6C8+igBZFXMJ7G3Pr8Dd13632aLng42wgAAACBeyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXN5bmRpY2F0aW9uLmNvbTo0NDMiLCJmZWF0dXJlIjoiVHJ1c3RUb2tlbnMiLCJleHBpcnkiOjE2NTI3NzQ0MDAsImlzU3ViZG9tYWluIjp0cnVlLCJpc1RoaXJkUGFydHkiOnRydWV9"><meta http-equiv="origin-trial" content="A88BWHFjcawUfKU3lIejLoryXoyjooBXLgWmGh+hNcqMK44cugvsI5YZbNarYvi3roc1fYbHA1AVbhAtuHZflgEAAAB2eyJvcmlnaW4iOiJodHRwczovL2dvb2dsZS5jb206NDQzIiwiZmVhdHVyZSI6IlRydXN0VG9rZW5zIiwiZXhwaXJ5IjoxNjUyNzc0NDAwLCJpc1N1YmRvbWFpbiI6dHJ1ZSwiaXNUaGlyZFBhcnR5Ijp0cnVlfQ=="><meta http-equiv="origin-trial" content="A8FHS1NmdCwGqD9DwOicnHHY+y27kdWfxKa0YHSGDfv0CSpDKRHTQdQmZVPDUdaFWUsxdgVxlwAd6o+dhJykPA0AAACWeyJvcmlnaW4iOiJodHRwczovL2RvdWJsZWNsaWNrLm5ldDo0NDMiLCJmZWF0dXJlIjoiQ29udmVyc2lvbk1lYXN1cmVtZW50IiwiZXhwaXJ5IjoxNjQzMTU1MTk5LCJpc1N1YmRvbWFpbiI6dHJ1ZSwiaXNUaGlyZFBhcnR5Ijp0cnVlLCJ1c2FnZSI6InN1YnNldCJ9"><meta http-equiv="origin-trial" content="A8zdXi6dr1hwXEUjQrYiyYQGlU3557y5QWDnN0Lwgj9ePt66XMEvNkVWOEOWPd7TP9sBQ25X0Q15Lr1Nn4oGFQkAAACceyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXN5bmRpY2F0aW9uLmNvbTo0NDMiLCJmZWF0dXJlIjoiQ29udmVyc2lvbk1lYXN1cmVtZW50IiwiZXhwaXJ5IjoxNjQzMTU1MTk5LCJpc1N1YmRvbWFpbiI6dHJ1ZSwiaXNUaGlyZFBhcnR5Ijp0cnVlLCJ1c2FnZSI6InN1YnNldCJ9"><meta http-equiv="origin-trial" content="A4/Htern2udN9w3yJK9QgWQxQFruxOXsXL7cW60DyCl0EZFGCSme/J33Q/WzF7bBkVvhEWDlcBiUyZaim5CpFQwAAACceyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXRhZ3NlcnZpY2VzLmNvbTo0NDMiLCJmZWF0dXJlIjoiQ29udmVyc2lvbk1lYXN1cmVtZW50IiwiZXhwaXJ5IjoxNjQzMTU1MTk5LCJpc1N1YmRvbWFpbiI6dHJ1ZSwiaXNUaGlyZFBhcnR5Ijp0cnVlLCJ1c2FnZSI6InN1YnNldCJ9"><meta http-equiv="origin-trial" content="AxujKG9INjsZ8/gUq8+dTruNvk7RjZQ1oFhhgQbcTJKDnZfbzSTE81wvC2Hzaf3TW4avA76LTZEMdiedF1vIbA4AAABueyJvcmlnaW4iOiJodHRwczovL2ltYXNkay5nb29nbGVhcGlzLmNvbTo0NDMiLCJmZWF0dXJlIjoiVHJ1c3RUb2tlbnMiLCJleHBpcnkiOjE2NTI3NzQ0MDAsImlzVGhpcmRQYXJ0eSI6dHJ1ZX0="><meta http-equiv="origin-trial" content="Azuce85ORtSnWe1MZDTv68qpaW3iHyfL9YbLRy0cwcCZwVnePnOmkUJlG8HGikmOwhZU22dElCcfrfX2HhrBPAkAAAB7eyJvcmlnaW4iOiJodHRwczovL2RvdWJsZWNsaWNrLm5ldDo0NDMiLCJmZWF0dXJlIjoiVHJ1c3RUb2tlbnMiLCJleHBpcnkiOjE2NTI3NzQ0MDAsImlzU3ViZG9tYWluIjp0cnVlLCJpc1RoaXJkUGFydHkiOnRydWV9"><meta http-equiv="origin-trial" content="A16nvcdeoOAqrJcmjLRpl1I6f3McDD8EfofAYTt/P/H4/AWwB99nxiPp6kA0fXoiZav908Z8etuL16laFPUdfQsAAACBeyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXRhZ3NlcnZpY2VzLmNvbTo0NDMiLCJmZWF0dXJlIjoiVHJ1c3RUb2tlbnMiLCJleHBpcnkiOjE2NTI3NzQ0MDAsImlzU3ViZG9tYWluIjp0cnVlLCJpc1RoaXJkUGFydHkiOnRydWV9"><meta http-equiv="origin-trial" content="AxBHdr0J44vFBQtZUqX9sjiqf5yWZ/OcHRcRMN3H9TH+t90V/j3ENW6C8+igBZFXMJ7G3Pr8Dd13632aLng42wgAAACBeyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXN5bmRpY2F0aW9uLmNvbTo0NDMiLCJmZWF0dXJlIjoiVHJ1c3RUb2tlbnMiLCJleHBpcnkiOjE2NTI3NzQ0MDAsImlzU3ViZG9tYWluIjp0cnVlLCJpc1RoaXJkUGFydHkiOnRydWV9"><meta http-equiv="origin-trial" content="A88BWHFjcawUfKU3lIejLoryXoyjooBXLgWmGh+hNcqMK44cugvsI5YZbNarYvi3roc1fYbHA1AVbhAtuHZflgEAAAB2eyJvcmlnaW4iOiJodHRwczovL2dvb2dsZS5jb206NDQzIiwiZmVhdHVyZSI6IlRydXN0VG9rZW5zIiwiZXhwaXJ5IjoxNjUyNzc0NDAwLCJpc1N1YmRvbWFpbiI6dHJ1ZSwiaXNUaGlyZFBhcnR5Ijp0cnVlfQ=="><meta http-equiv="origin-trial" content="A8FHS1NmdCwGqD9DwOicnHHY+y27kdWfxKa0YHSGDfv0CSpDKRHTQdQmZVPDUdaFWUsxdgVxlwAd6o+dhJykPA0AAACWeyJvcmlnaW4iOiJodHRwczovL2RvdWJsZWNsaWNrLm5ldDo0NDMiLCJmZWF0dXJlIjoiQ29udmVyc2lvbk1lYXN1cmVtZW50IiwiZXhwaXJ5IjoxNjQzMTU1MTk5LCJpc1N1YmRvbWFpbiI6dHJ1ZSwiaXNUaGlyZFBhcnR5Ijp0cnVlLCJ1c2FnZSI6InN1YnNldCJ9"><meta http-equiv="origin-trial" content="A8zdXi6dr1hwXEUjQrYiyYQGlU3557y5QWDnN0Lwgj9ePt66XMEvNkVWOEOWPd7TP9sBQ25X0Q15Lr1Nn4oGFQkAAACceyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXN5bmRpY2F0aW9uLmNvbTo0NDMiLCJmZWF0dXJlIjoiQ29udmVyc2lvbk1lYXN1cmVtZW50IiwiZXhwaXJ5IjoxNjQzMTU1MTk5LCJpc1N1YmRvbWFpbiI6dHJ1ZSwiaXNUaGlyZFBhcnR5Ijp0cnVlLCJ1c2FnZSI6InN1YnNldCJ9"><meta http-equiv="origin-trial" content="A4/Htern2udN9w3yJK9QgWQxQFruxOXsXL7cW60DyCl0EZFGCSme/J33Q/WzF7bBkVvhEWDlcBiUyZaim5CpFQwAAACceyJvcmlnaW4iOiJodHRwczovL2dvb2dsZXRhZ3NlcnZpY2VzLmNvbTo0NDMiLCJmZWF0dXJlIjoiQ29udmVyc2lvbk1lYXN1cmVtZW50IiwiZXhwaXJ5IjoxNjQzMTU1MTk5LCJpc1N1YmRvbWFpbiI6dHJ1ZSwiaXNUaGlyZFBhcnR5Ijp0cnVlLCJ1c2FnZSI6InN1YnNldCJ9"><link rel="preload" href="https://adservice.google.co.th/adsid/integrator.js?domain=framesynthesis.com" as="script"><script type="text/javascript" src="https://adservice.google.co.th/adsid/integrator.js?domain=framesynthesis.com"></script><link rel="preload" href="https://adservice.google.com/adsid/integrator.js?domain=framesynthesis.com" as="script"><script type="text/javascript" src="https://adservice.google.com/adsid/integrator.js?domain=framesynthesis.com"></script><script charset="utf-8" src="https://platform.twitter.com/js/button.1c2a6e168692ffea6cc8d4efc5b6f6bc.js"></script></head>
<body>
	
	
		<header>
	<div class="container">
		<a class="logo" href="/"></a>

		<div id="mobile-menu-button"></div>
		<nav>
			<ul>
				<li><a href="/">HOME</a></li><li><a href="/about/">ABOUT</a></li><li><a href="https://framesynthesis.jp/">JAPANESE</a></li>
			</ul>
		</nav>
	</div>
</header>
<div id="mobile-menu" class="hidden">
	<ul>
		<li><a href="/">Home</a></li>
		<li><a href="/about/">About</a></li>
		<li><a href="https://framesynthesis.jp/drivingsimulator/maps/">JAPANESE</a></li>
	</ul>
</div>

    
    
	
	<div class="container-728">
		<style>
#drivingsimulator {
	position: relative;
	width: 728px;
	height: 546px;
	margin: 20px auto;
}

@media (max-width:750px) {
	.header {
		display: none;
	}

	body, html {
		height: 100%;
	}

	#drivingsimulator {
		width: calc(100% + 30px);
		height: 400;
		margin: 0 -15px;

		overflow: hidden;
		-webkit-overflow-scrolling:touch;
	}
}
</style>
<ins class="adsbygoogle adsense_horizontal center-block" style="display: block; width: 728px; height: 90px;" data-ad-client="ca-pub-8236350388660353" data-ad-slot="8603502744" data-adsbygoogle-status="done" data-ad-status="filled"><ins id="aswift_0_expand" style="border: none; height: 90px; width: 728px; margin: 0px; padding: 0px; position: relative; visibility: visible; background-color: transparent; display: inline-table;" tabindex="0" title="Advertisement" aria-label="Advertisement"><ins id="aswift_0_anchor" style="border: none; height: 90px; width: 728px; margin: 0px; padding: 0px; position: relative; visibility: visible; background-color: transparent; display: block;"><iframe id="aswift_0" name="aswift_0" style="left:0;position:absolute;top:0;border:0;width:728px;height:90px;" sandbox="allow-forms allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts allow-top-navigation-by-user-activation" width="728" height="90" frameborder="0" marginwidth="0" marginheight="0" vspace="0" hspace="0" allowtransparency="true" scrolling="no" src="https://googleads.g.doubleclick.net/pagead/ads?client=ca-pub-8236350388660353&amp;output=html&amp;h=90&amp;slotname=8603502744&amp;adk=1529036226&amp;adf=1839787983&amp;pi=t.ma~as.8603502744&amp;w=728&amp;lmt=1642696138&amp;rafmt=12&amp;psa=1&amp;format=728x90&amp;url=https%3A%2F%2Fframesynthesis.com%2Fdrivingsimulator%2Fmaps%2F&amp;flash=0&amp;wgl=1&amp;uach=WyJXaW5kb3dzIiwiOC4wLjAiLCJ4ODYiLCIiLCI5OC4wLjQ3NTguMTAyIixbXSxudWxsLG51bGwsIjY0IixbWyIgTm90IEE7QnJhbmQiLCI5OS4wLjAuMCJdLFsiQ2hyb21pdW0iLCI5OC4wLjQ3NTguMTAyIl0sWyJHb29nbGUgQ2hyb21lIiwiOTguMC40NzU4LjEwMiJdXV0.&amp;dt=1645615923351&amp;bpp=174&amp;bdt=3424&amp;idt=2883&amp;shv=r20220217&amp;mjsv=m202202090102&amp;ptt=9&amp;saldr=aa&amp;abxe=1&amp;cookie=ID%3D6aeedf4108e821c9-22aa8bbeb9d000ef%3AT%3D1645615721%3ART%3D1645615721%3AS%3DALNI_Ma5o0WVDvoXpa1IcU4R185hL_pduQ&amp;correlator=4902684997950&amp;frm=20&amp;pv=2&amp;ga_vid=2131031976.1645615783&amp;ga_sid=1645615926&amp;ga_hid=1865730108&amp;ga_fc=1&amp;u_tz=420&amp;u_his=1&amp;u_h=768&amp;u_w=1366&amp;u_ah=728&amp;u_aw=1366&amp;u_cd=24&amp;u_sd=1&amp;dmc=4&amp;adx=311&amp;ady=130&amp;biw=1349&amp;bih=625&amp;scr_x=0&amp;scr_y=300&amp;eid=42531397%2C44750773%2C44756895%2C44756897%2C44756431%2C21067496&amp;oid=2&amp;pvsid=1419147071680338&amp;pem=21&amp;tmod=411122689&amp;uas=0&amp;nvt=2&amp;ref=https%3A%2F%2Fsearch.yahoo.com%2F&amp;eae=0&amp;fc=896&amp;brdim=0%2C0%2C0%2C0%2C1366%2C0%2C1366%2C728%2C1366%2C625&amp;vis=1&amp;rsz=%7C%7CeE%7C&amp;abl=CS&amp;pfx=0&amp;fu=256&amp;bc=31&amp;ifi=1&amp;uci=a!1&amp;fsb=1&amp;xpc=bliK4YDNR0&amp;p=https%3A//framesynthesis.com&amp;dtd=3401" data-google-container-id="a!1" data-google-query-id="CLW1kujclfYCFYOeSwUdJ74Ipw" data-load-complete="true"></iframe></ins></ins></ins>
<script src="https://partner.googleadservices.com/gampad/cookie.js?domain=framesynthesis.com&amp;callback=_gfp_s_&amp;client=ca-pub-8236350388660353&amp;cookie=ID%3D6aeedf4108e821c9-22aa8bbeb9d000ef%3AT%3D1645615721%3ART%3D1645615721%3AS%3DALNI_Ma5o0WVDvoXpa1IcU4R185hL_pduQ"></script><script src="https://pagead2.googlesyndication.com/pagead/managed/js/adsense/m202202090102/show_ads_impl_fy2019.js" id="google_shimpl"></script><script async="" src="//www.google-analytics.com/analytics.js"></script><script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>
<script async="" src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>

<div id="drivingsimulator">
	<iframe width="100%" height="100%" src="https://korinvr.com/bin/drivingsimulatorgm/24/" frameborder="0" scrolling="no"></iframe>
</div>
<div class="sns-buttons">
	<div class="sns-button" style="left:0px;">
		<iframe id="twitter-widget-0" scrolling="no" frameborder="0" allowtransparency="true" allowfullscreen="true" class="twitter-share-button twitter-share-button-rendered twitter-tweet-button" style="position: static; visibility: visible; width: 73px; height: 20px;" title="Twitter Tweet Button" src="https://platform.twitter.com/widgets/tweet_button.a58e82e150afc25eb5372dd55a98b778.en.html#dnt=false&amp;id=twitter-widget-0&amp;lang=en&amp;original_referer=https%3A%2F%2Fframesynthesis.com%2Fdrivingsimulator%2Fmaps%2F&amp;size=m&amp;text=Driving%20Simulator%20on%20Google%20Maps%20-%20Frame%20Synthesis&amp;time=1645615949907&amp;type=share&amp;url=https%3A%2F%2Fframesynthesis.com%2Fdrivingsimulator%2Fmaps%2F&amp;via=korinVR_en"></iframe>
	</div>
</div>

<ins class="adsbygoogle adsense_horizontal center-block" style="display: block; width: 728px; height: 90px;" data-ad-client="ca-pub-8236350388660353" data-ad-slot="8603502744" data-adsbygoogle-status="done" data-ad-status="filled"><ins id="aswift_1_expand" style="border: none; height: 90px; width: 728px; margin: 0px; padding: 0px; position: relative; visibility: visible; background-color: transparent; display: inline-table;" tabindex="0" title="Advertisement" aria-label="Advertisement"><ins id="aswift_1_anchor" style="border: none; height: 90px; width: 728px; margin: 0px; padding: 0px; position: relative; visibility: visible; background-color: transparent; display: block;"><iframe id="aswift_1" name="aswift_1" style="left:0;position:absolute;top:0;border:0;width:728px;height:90px;" sandbox="allow-forms allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts allow-top-navigation-by-user-activation" width="728" height="90" frameborder="0" marginwidth="0" marginheight="0" vspace="0" hspace="0" allowtransparency="true" scrolling="no" src="https://googleads.g.doubleclick.net/pagead/ads?client=ca-pub-8236350388660353&amp;output=html&amp;h=90&amp;slotname=8603502744&amp;adk=1529036226&amp;adf=1171094417&amp;pi=t.ma~as.8603502744&amp;w=728&amp;lmt=1642696138&amp;rafmt=12&amp;psa=1&amp;format=728x90&amp;url=https%3A%2F%2Fframesynthesis.com%2Fdrivingsimulator%2Fmaps%2F&amp;flash=0&amp;wgl=1&amp;uach=WyJXaW5kb3dzIiwiOC4wLjAiLCJ4ODYiLCIiLCI5OC4wLjQ3NTguMTAyIixbXSxudWxsLG51bGwsIjY0IixbWyIgTm90IEE7QnJhbmQiLCI5OS4wLjAuMCJdLFsiQ2hyb21pdW0iLCI5OC4wLjQ3NTguMTAyIl0sWyJHb29nbGUgQ2hyb21lIiwiOTguMC40NzU4LjEwMiJdXV0.&amp;dt=1645615923526&amp;bpp=8&amp;bdt=3599&amp;idt=3902&amp;shv=r20220217&amp;mjsv=m202202090102&amp;ptt=9&amp;saldr=aa&amp;abxe=1&amp;cookie=ID%3D6aeedf4108e821c9-22aa8bbeb9d000ef%3AT%3D1645615721%3ART%3D1645615721%3AS%3DALNI_Ma5o0WVDvoXpa1IcU4R185hL_pduQ&amp;prev_fmts=728x90&amp;correlator=4902684997950&amp;frm=20&amp;pv=1&amp;ga_vid=2131031976.1645615783&amp;ga_sid=1645615926&amp;ga_hid=1865730108&amp;ga_fc=1&amp;u_tz=420&amp;u_his=1&amp;u_h=768&amp;u_w=1366&amp;u_ah=728&amp;u_aw=1366&amp;u_cd=24&amp;u_sd=1&amp;dmc=4&amp;adx=311&amp;ady=870&amp;biw=1349&amp;bih=625&amp;scr_x=0&amp;scr_y=300&amp;eid=42531397%2C44750773%2C44756895%2C44756897%2C44756431%2C21067496&amp;oid=2&amp;pvsid=1419147071680338&amp;pem=21&amp;tmod=411122689&amp;uas=0&amp;nvt=2&amp;ref=https%3A%2F%2Fsearch.yahoo.com%2F&amp;eae=0&amp;fc=896&amp;brdim=0%2C0%2C0%2C0%2C1366%2C0%2C1366%2C728%2C1366%2C625&amp;vis=1&amp;rsz=%7C%7CeE%7C&amp;abl=CS&amp;pfx=0&amp;fu=256&amp;bc=31&amp;ifi=2&amp;uci=a!2&amp;fsb=1&amp;xpc=OBd1sT8kT7&amp;p=https%3A//framesynthesis.com&amp;dtd=4152" data-google-container-id="a!2" data-google-query-id="CK3e6OjclfYCFXe1SwUd-V4AmQ" data-load-complete="true"></iframe></ins></ins></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>
<script async="" src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>

<h2 id="whats-this">What’s this?</h2>
<p>You can drive vehicles on Google Maps. You can drive safely, ignore roads, park, race on a circuit, and travel around the world. You can play in any way you want!</p>
<h2 id="how-to-drive">How to drive</h2>
<p>Left / Right arrow keys: Steering<br>
Up / Down arrow keys: Go forward and backward</p>
<p>On smartphones or tablets, use the virtual stick.</p>
<h2 id="credits">Credits</h2>
<p>Programming - 
Katsuomi Kobayashi (<a href="https://twitter.com/korinVR_en">@korinVR_en</a>)


</p>
<h2 id="technology">Technology</h2>
<p>TypeScript, Google Maps API, Three.js, Box2D</p>
<h2 id="history">History</h2>
<h3 id="jan-2022">Jan 2022</h3>
<ul>
<li><strong>Bus is back!</strong></li>
<li><strong>Location search is back (experimentally)</strong></li>
<li><strong>Remove “3D” from the title</strong></li>
<li>Implement game-like automatic camera</li>
<li>Remove zoom buttons</li>
<li>Tweak the button layout and design</li>
<li>Clean up the preset locations</li>
<li>Add front wheel steering rotation</li>
<li>Add fake vehicle shadows</li>
</ul>
<p><a href="history/">More…</a></p>

	</div>


	<footer>
		<div class="container">
			<small>Copyright (C) 2014-2022 <a href="https://framesynthesis.com/">Frame Synthesis</a></small>
		</div>
	</footer>
	
	<script>
function toggleMenu() {
	if (menu.className != "visible") {
		menu.className = "visible";
	} else {
		menu.className = "hidden";
	}
}

var menu = document.getElementById("mobile-menu");
if (menu) {
	var eventName = "click";
	if ("ontouchstart" in document.documentElement) {
		eventName = "touchstart";
	}
	document.getElementById("mobile-menu-button").addEventListener(eventName, toggleMenu);
}
</script>

	
<script src="//platform.twitter.com/widgets.js" id="twitter-wjs" async=""></script>

	<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-44941967-2', 'framesynthesis.com');
  ga('send', 'pageview');

</script>



<iframe scrolling="no" frameborder="0" allowtransparency="true" src="https://platform.twitter.com/widgets/widget_iframe.a58e82e150afc25eb5372dd55a98b778.html?origin=https%3A%2F%2Fframesynthesis.com" title="Twitter settings iframe" style="display: none;"></iframe><ins class="adsbygoogle adsbygoogle-noablate" data-adsbygoogle-status="done" style="display: none !important;" data-ad-status="unfilled"><ins id="aswift_2_expand" style="border: none; height: 0px; width: 0px; margin: 0px; padding: 0px; position: relative; visibility: visible; background-color: transparent; display: inline-table;" tabindex="0" title="Advertisement" aria-label="Advertisement"><ins id="aswift_2_anchor" style="border: none; height: 0px; width: 0px; margin: 0px; padding: 0px; position: relative; visibility: visible; background-color: transparent; display: block;"><iframe id="aswift_2" name="aswift_2" style="left:0;position:absolute;top:0;border:0;width:undefinedpx;height:undefinedpx;" sandbox="allow-forms allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts allow-top-navigation-by-user-activation" frameborder="0" marginwidth="0" marginheight="0" vspace="0" hspace="0" allowtransparency="true" scrolling="no" src="https://googleads.g.doubleclick.net/pagead/ads?client=ca-pub-8236350388660353&amp;output=html&amp;adk=1812271804&amp;adf=3025194257&amp;lmt=1642696138&amp;plat=1%3A1024%2C2%3A1024%2C3%3A32%2C4%3A32%2C9%3A32776%2C16%3A8388608%2C17%3A32%2C24%3A32%2C25%3A32%2C30%3A1081344%2C32%3A32&amp;format=0x0&amp;url=https%3A%2F%2Fframesynthesis.com%2Fdrivingsimulator%2Fmaps%2F&amp;ea=0&amp;flash=0&amp;pra=7&amp;wgl=1&amp;uach=WyJXaW5kb3dzIiwiOC4wLjAiLCJ4ODYiLCIiLCI5OC4wLjQ3NTguMTAyIixbXSxudWxsLG51bGwsIjY0IixbWyIgTm90IEE7QnJhbmQiLCI5OS4wLjAuMCJdLFsiQ2hyb21pdW0iLCI5OC4wLjQ3NTguMTAyIl0sWyJHb29nbGUgQ2hyb21lIiwiOTguMC40NzU4LjEwMiJdXV0.&amp;dt=1645615923707&amp;bpp=20&amp;bdt=3780&amp;idt=4249&amp;shv=r20220217&amp;mjsv=m202202090102&amp;ptt=9&amp;saldr=aa&amp;abxe=1&amp;cookie=ID%3D6aeedf4108e821c9-22aa8bbeb9d000ef%3AT%3D1645615721%3ART%3D1645615721%3AS%3DALNI_Ma5o0WVDvoXpa1IcU4R185hL_pduQ&amp;prev_fmts=728x90%2C728x90&amp;nras=1&amp;correlator=4902684997950&amp;frm=20&amp;pv=1&amp;ga_vid=2131031976.1645615783&amp;ga_sid=1645615926&amp;ga_hid=1865730108&amp;ga_fc=1&amp;u_tz=420&amp;u_his=1&amp;u_h=768&amp;u_w=1366&amp;u_ah=728&amp;u_aw=1366&amp;u_cd=24&amp;u_sd=1&amp;dmc=4&amp;adx=-12245933&amp;ady=-12245933&amp;biw=1349&amp;bih=625&amp;scr_x=0&amp;scr_y=300&amp;eid=42531397%2C44750773%2C44756895%2C44756897%2C44756431%2C21067496&amp;oid=2&amp;pvsid=1419147071680338&amp;pem=21&amp;tmod=411122689&amp;uas=0&amp;nvt=2&amp;ref=https%3A%2F%2Fsearch.yahoo.com%2F&amp;eae=2&amp;fc=896&amp;brdim=0%2C0%2C0%2C0%2C1366%2C0%2C1366%2C728%2C1366%2C625&amp;vis=1&amp;rsz=%7C%7Cs%7C&amp;abl=NS&amp;fu=32768&amp;bc=31&amp;ifi=3&amp;uci=a!3&amp;fsb=1&amp;dtd=4352" data-google-container-id="a!3" data-load-complete="true"></iframe></ins></ins></ins><iframe src="https://www.google.com/recaptcha/api2/aframe" width="0" height="0" style="display: none;"></iframe><iframe id="rufous-sandbox" scrolling="no" frameborder="0" allowtransparency="true" allowfullscreen="true" style="position: absolute; visibility: hidden; display: none; width: 0px; height: 0px; padding: 0px; border: none;" title="Twitter analytics iframe"></iframe></body><iframe id="google_esf" name="google_esf" src="https://googleads.g.doubleclick.net/pagead/html/r20220217/r20190131/zrt_lookup.html" style="display: none;"></iframe></html>
