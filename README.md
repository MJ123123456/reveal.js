<!doctype html>

<!-- 
Willkommen. In diesen Kommentaren erkläre ich Dir ein bißchen den Code, 
so dass Du einfach eine eigene Präsentation gestalten kannst.
Um den ganzen ersten Bereich musst Du Dich fast gar nicht kümmern. Nichts davon taucht als Inhalt in Deiner Präsentation auf.
Stattdessen wird festgelegt, wie die Präsentation funktionieren wird.
Was Du tun solltest:
1. Für Suchmaschinen und Nutzende ist es hilfreich, wenn Du den Titel, Deinen Namen und eine Beschreibung angibst.
(Der Titel wird ganz oben im Browser sichtbar sein, damit Nutzende wissen, wo im Internet sie sich gerade befinden.)
2. Und dann solltest Du Dir noch diese Zeile ansehen:
<link rel="stylesheet" href="css/theme/black.css" id="theme">
Anstelle von black, kannst Du auch white, simple, blood, night, moon ... setzen. Beispiele sind in der Präsentation verlinkt. 
Danach kannst Du runterscrollen bis zum nächsten ausführlichen Kommentar.  
-->

<html lang="de">

	<head>
		<meta charset="utf-8">

		<title>Edunautika</title>

		<meta name="description" content="Nachgebastelt mit github">
		<meta name="author" content="FoBiD">

		<meta name="apple-mobile-web-app-capable" content="yes">
		<meta name="apple-mobile-web-app-status-bar-style" content="moon-translucent">

		<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

		<link rel="stylesheet" href="css/reveal.css">
		<link rel="stylesheet" href="css/theme/black.css" id="theme">

		<!-- Theme used for syntax highlighting of code -->
		<link rel="stylesheet" href="lib/css/zenburn.css">

		<!-- Printing and PDF exports -->
		<script>
			var link = document.createElement( 'link' );
			link.rel = 'stylesheet';
			link.type = 'text/css';
			link.href = window.location.search.match( /print-pdf/gi ) ? 'css/print/pdf.css' : 'css/print/paper.css';
			document.getElementsByTagName( 'head' )[0].appendChild( link );
		</script>

		<!--[if lt IE 9]>
		<script src="lib/js/html5shiv.js"></script>
		<![endif]-->
	</head>

	<body>

		<div class="reveal">

		
			<!-- 
Weiter geht es mit den Erklärungen!
Ab hier wird es dann spannend! 
Denn ab hier gestaltest Du Deine Slides!
Ein neues Slide beginnt immer mit <section> Dazwischen stehen die Inhalte. Sie werden mit HTML geschrieben. 
Danach wird das Slide mit </section> beendet.  
-->
			<div class="slides">
				<section>
					<h1>Willkommen</h1>
					<h3>Das ist meine Präsentation.</h3>
					<p>
						<small>Erstellt von FoBiD | <a href="https://eBildungslabor.de">eBildungslabor</a></small>
					</p>
						
						<aside class="notes">
	Hier stehen meine Notizen
</aside>
					
				</section>
<!-- Wenn Du zweimal <section> schreibst, kannst Du Slides 'nach unten' setzen. 
-->
				<section>
					<section>
						<section>
						<h2>Hier sehen Sie  dreifache slides.</h2>
						<p>Diese Funktion ist cool.</p>
						
					</section>
				
					<section>
						<h2>Hier sehen Sie  dreifache slides.</h2>
						<p>Diese Funktion ist auch cool.</p>
						
					</section>
				</section>
<!-- Wenn Du zweimal <section id="fragments"> schreibst, kannst Du Text bzw. Inhalte Schritt für Schritt aufbauen. 
-->
	
				<section>
					<section id="fragments">
						<h2>Jetzt kommen die Punkte nacheinander.</h2>
						<p>H</p>
						<p class="fragment">A</p>
						<p class="fragment">L</p>
						<p class="fragment">L</p>
						<p class="fragment">O</p>
					</section>
					</section>

				<section>
						<section id="fragments">
						<h2>Viele Darstellungsmöglichkeiten</h2>
				
						<p class="fragment grow">vergrößern</p>
						<p class="fragment shrink">verkleinern</p>
						<p class="fragment fade-out">ausblenden</p>
					
						<p class="fragment fade-in-then-out">einblenden und ausblenden</p>
						<p class="fragment fade-in-then-semi-out">einblenden und halb ausblenden</p>
						<p>Mit Farben markieren:<span class="fragment highlight-red">rot</span> <span class="fragment highlight-blue">blau</span> <span class="fragment highlight-green">grün</span></p>
					</section>
				</section>				

				
				<section id="themes">
					<h2>Layout</h2>
					<p>
		Das Design kannst Du im Kopf des Dokuments festlegen. Hier ist eine Vorschau.<br>
						<!-- Hacks to swap themes after the page has loaded. Not flexible and only intended for the reveal.js demo deck. -->
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/black.css'); return false;">Black (default)</a> -
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/white.css'); return false;">White</a> -
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/league.css'); return false;">League</a> -
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/sky.css'); return false;">Sky</a> -
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/beige.css'); return false;">Beige</a> -
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/simple.css'); return false;">Simple</a> <br>
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/serif.css'); return false;">Serif</a> -
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/blood.css'); return false;">Blood</a> -
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/night.css'); return false;">Night</a> -
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/moon.css'); return false;">Moon</a> -
						<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/solarized.css'); return false;">Solarized</a>
					</p>
</section>
				

<!-- Wenn Du nicht nur <section> schreibst, um ein Slide zu beginnen, 
sondern <section data background="..."> kannst Du Farbe, Bilder, Gifs oder Videos als Hintergrund setzen.
-->
				
					<section data-background="#2100ff">
						<h2>Slides mit farbigem Hintergrund</h2>
						
					</section>
					<section data-background="https://www.oercamp.de/wp-content/uploads/2017/12/OERde17-OERCamp-Tilman-Vogler-Tag-2-053_web.jpg">
						<h2>Slides mit Bild als Hintergrund</h2>
						
					</section>
					
			
					<section data-background="https://media.giphy.com/media/l2Je3ktsieOfOGa1G/giphy.gif">
						<h2>Slides mit Gif als Hintergrund</h2>
					</section>
				
				
				
				<section>
					<h2>Überblick oder kurze Pause?</h2>
					
     
					<p>Drücke auf Esc oder B. Und mit Klick auf S bekommst Du eine Speakers-Ansicht</p>
					
					<aside class="notes">
	Hier steht Text, der für die vortragenden Person wichtig ist, aber nicht direkt in der Präsentation nicht auftaucht.
</aside>
				</section>

			
				<section>
					<h1>JETZT bist Du dran!</h1>
					<p>
						👉 <a href="https://github.com/eBildungslabor/slides/blob/master/README.md">Lies Dir die Schritt für Schritt Anleitung durch.</a> <br>
					</p>
				</section>

				
<!-- 
Jeztzt sind wir fertig mit den Slides.
Abschließend folgen noch einige Einstellungen. 
Insbesondere kannst Du bei 'transition' festlegen, wie der Übergang zwischen Slides gestaltet sein soll.   
-->
	
			</div>

		</div>

		<script src="lib/js/head.min.js"></script>
		<script src="js/reveal.js"></script>

		<script>
			// More info https://github.com/hakimel/reveal.js#configuration
			Reveal.initialize({
				controls: true,
				progress: true,
				history: true,
				center: true,
				transition: 'zoom', // none/fade/slide/convex/concave/zoom
				// More info https://github.com/hakimel/reveal.js#dependencies
				dependencies: [
					{ src: 'lib/js/classList.js', condition: function() { return !document.body.classList; } },
					{ src: 'plugin/markdown/marked.js', condition: function() { return !!document.querySelector( '[data-markdown]' ); } },
					{ src: 'plugin/markdown/markdown.js', condition: function() { return !!document.querySelector( '[data-markdown]' ); } },
					{ src: 'plugin/highlight/highlight.js', async: true, callback: function() { hljs.initHighlightingOnLoad(); } },
					{ src: 'plugin/search/search.js', async: true },
					{ src: 'plugin/zoom-js/zoom.js', async: true },
					{ src: 'plugin/notes/notes.js', async: true }
				]
			});
		</script>

	</body>
</html>
