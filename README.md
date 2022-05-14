# La radio guerrillass

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Inserting Audio Using embed Element</title>
</head>
<body>
    <embed src="http://giss.tv:8000/guerrillaradio.mp3">
    <embed src="http://giss.tv:8000/guerrillaradio.ogg">
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Inserting Audio Using object Element</title>
</head>
<body>
    <object data="http://giss.tv:8000/guerrillaradio.mp3></object>
    <object data="http://giss.tv:8000/guerrillaradio.ogg"></object>
</body>
</html>
                                                         
                                                         
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Linking Audio Files in HTML</title>
</head>
<body>
    <p><a href="http://giss.tv:8000/guerrillaradio.mp3">Track 1</a></p>
    <p><a href="http://giss.tv:8000/guerrillaradio.ogg">Track 2</a></p>
</body>
</html>
                                                       
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Specify Alternate Sources for audio Element in HTML</title>
</head>
<body>
    <audio controls="controls">
        <source src="http://giss.tv:8000/guerrillaradio.mp3" type="audio/mpeg">
        <source src="http://giss.tv:8000/guerrillaradio.ogg" type="audio/ogg">
        Your browser does not support the HTML5 audio element.
    </audio>
</body>
</html>  
                                                                             
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
                                                       
