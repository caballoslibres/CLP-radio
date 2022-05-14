# La radio guerrillas

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Embedding Audio into an HTML Page</title>
</head>
<body>
	<audio controls="controls" src="http://giss.tv:8000/guerrillaradio.ogg">
        Your browser does not support the HTML5 audio element.
    </audio>
</body>
</html> 


<!DOCTYPE html>
<html>
<body>

<h1>The audio autoplay attribute</h1>

<p>Click on the play button to play a sound:</p>

<audio controls autoplay>
  <source src="http://giss.tv:8000/guerrillaradio.ogg" type="audio/ogg">
  <source src="http://giss.tv:8000/guerrillaradio.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</body>
</html>
