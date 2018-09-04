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
			    	<p id="temp">21.0C</p>
			    </header>
				<section>
					<ul class="icons">
						<li><a href="#" class="fa-minus" onclick="decrease()">Decrease</a></li>
						<li><a href="#" class="fa-plus" onclick="increase()">Increase</a></li>
					</ul>
				</section>
			</section>        
            <footer>
			</footer>        
        </div>
		<script>
			var current_temp = 21.0;

			if ('addEventListener' in window) {
				window.addEventListener('load', function() { document.body.className = document.body.className.replace(/\bis-loading\b/, ''); });
			}

			function update_temp() {
				document.getElementById("temp").innerHTML = current_temp + "C";
			}

			function decrease() {
				current_temp = current_temp - 0.5;
				update_temp();
			}

			function increase() {
				current_temp = current_temp + 0.5;
				update_temp();
			}

		</script>
	</body>
</html>