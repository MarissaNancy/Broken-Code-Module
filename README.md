# Broken-Code-Module
<!DOCTYPE html>
<html>
<head>
	<title>Grumpy Cat Fan Page</title>
	<!-- Latest compiled and minified CSS -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">
	<!-- Linking CSS -->
	<link rel="stylesheet" type="text/css" href="style.css">
	<!-- Linking jQuery -->
	<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
	<!-- Linking Google Fonts -->
	<link href='https://fonts.googleapis.com/css?family=Montserrat|Roboto+Slab|Yellowtail' rel='stylesheet' type='text/css'>
</head>
<body>

<div class="container">

	<div class="jumbotron bg-primary text-center">
		<h1>Grumpy Cat Fan Page!</h1>
	</div>

	<div class="row">
	
		<div class="col-sm-6">
			<div class="panel panel-primary">
				<div class="panel-heading">About Grumpy Cat</div>
				<div class="panel-body">
					<p>
						Tardar Sauce (born April 4, 2012), is a cat and Internet celebrity known for her "grumpy" facial expression, and thus known by the common name Grumpy Cat. Her owner, Tabatha Bundesen, says that her permanently grumpy-looking face is due to an underbite and feline dwarfism.
					</p> 
					<p>
						Grumpy Cat's popularity originated from a picture posted to the social news website Reddit by Bundesen's brother Bryan on September 22, 2012. It was made into an image macro with grumpy captions. As of March 14, 2016, "The Official Grumpy Cat" page on Facebook has over 8.5 million likes. Grumpy Cat was featured on the front page of The Wall Street Journal on May 30, 2013, and on the cover of New York magazine on October 7, 2013.
					</p>
					<p>
						In August 2015 it was announced that Grumpy Cat would get her own animatronic waxwork at Madame Tussauds in San Francisco. Tardar Sauce has a twin brother named Pokey, who sometimes also appears in Tardar Sauce's memes.
					</p>
					<p>
						Read more at: <a href="https://en.wikipedia.org/wiki/Grumpy_Cat">https://en.wikipedia.org/wiki/Grumpy_Cat</a>
					</p>
				</div>
			</div>
		</div>

		<div class="col-sm-6">
			<div class="well text-center">
				<div>
					<img class="img-responsive" src="http://pre10.deviantart.net/1d23/th/pre/i/2013/070/1/e/grumpy_cat_by_bwcopy-d5xod2v.jpg">
				</div>
			</div>
		</div>

	</div>

	<br><br>

	<div class="row text-center">
			
		<div class="col-sm-6">
			<button class="btn" id="boxGrow">Grow</button>
			<button class="btn" id="boxShrink">Shrink</button>
			<br>
			<br>
			<div class="well text-center">
				<img id="box" src="http://img10.deviantart.net/459b/i/2014/181/4/8/grumpy_cat_by_elicoronel16-d7on00y.png">
			</div>
		</div>

		<div class="col-sm-6 text-center">
			<button class="btn" id="textOrange">Orange</button>
			<button class="btn" id="textPink">Pink</button>
			<button class="btn" id="textGreen">Green</button>
			<br>
			<br>
			<div class="well text-center">
				<p id="funText">Grumpy Cat Rules!</p>
			</div>
		</div>

	</div>

	<br><br><br><br>

	<div class="row">

		<div class="col-sm-6 text-center">
			<button class="btn btn-primary form-control" id="factButton">Random Grumpy Cat Fact</button>
			<div class="well text-center">
				<div>
					<p id="factText">Click the button for a random Grumpy Cat fact!</p>
				</div>
			</div>
		</div>

		<div class="col-sm-6">
			<div class="panel panel-primary">
				<div class="panel-heading">List Of Grumpy Cat's Favorite Things</div>
				<div class="panel-body">
					<ol>
						<li>Sleep</li>
						<li>Food</li>
						<li>Catnip</li>
						<li>Pizza</li>
						<li>Not Liking Things</li>
					</ol>
				</div>
			</div>
		</div>

	</div>

</div>

<!-- Linking our JavaScript file -->
<script type="text/javascript" src="logic.js"></script>
</body>
</html>
