# Making Sounds
1. Download Sonic Pi: https://sonic-pi.net/
    copy some of the example code from the homepage
    play with some of the parameters until you get a sound that you want 
    
# Recording and Exporting Sounds
2. Export your track: http://sonic-pi.mehackit.org/exercises/en/08-exporting-your-track/01-exporting-your-track.html 
    click "record" to capture your sound
    click "run" to start the sound
    when you get enough of your sound recorded, click "stop," then click on "rec" again to stop the recording
    save your file as a .wav

# Hosting Sounds
3. Make a github account: github.com
	make a new repository
	initate with a "read me" file
	upload your wave file
	"commit" it
	click into the file and copy the url

# Using Our Hosted Sound in An Onclick Event
4. Add ```?raw=true``` to the end of your sound url 
	copy that whole url
	then add the url to the following bit of code (replace the URL already in the code with your own) 
	embed the code onto your own website, and enjoy a user feedback sound of your own creation!
  
```
<html>
<body>
    <script>
  function play(){
       var audio = document.getElementById("audio");
       audio.play();
                 }
   </script>
<input type="button" value="PLAY"  onclick="play()">
<audio id="audio" src="https://github.com/milesccoleman/sounds/blob/master/sawing-wood-daniel_simon.mp3?raw=true" ></audio>
 </body>
 </html>
