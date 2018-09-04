<html>
	<head>
		<title>PLC Demo Page</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<link rel="stylesheet" href="./themes/Identity/assets/css/main.min.css" />
		<noscript><link rel="stylesheet" href="./themes/Identity/assets/css/noscript.css" /></noscript>
	</head>
	<body class="is-loading">
	    <div id="wrapper">
            <section id="main">
			    <header>
			    	<h1>Living Room</h1>
			    	<p>21C</p>
			    </header>
				<section>
					<ul class="icons">
						<li><a target="_new" href="https://github.com/koenkarsten" class="fa-plus">Increase</a></li>
						<li><a target="_new" href="https://nl.linkedin.com/in/koenkarsten" class="fa-minus">Decrease</a></li>
					</ul>
				</section>
			</section>        
            <footer>
			</footer>        
        </div>
		<script>
			if ('addEventListener' in window) {
				window.addEventListener('load', function() { document.body.className = document.body.className.replace(/\bis-loading\b/, ''); });
			}
		</script>
	</body>
</html>