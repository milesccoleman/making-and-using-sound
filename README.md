# Making Sounds
1. Download Sonic Pi: https://sonic-pi.net/
2. Copy some of the example code from the homepage
3. Play with some of the parameters until you get a sound that you want 
    
# Recording and Exporting Sounds
4. Export your track: http://sonic-pi.mehackit.org/exercises/en/08-exporting-your-track/01-exporting-your-track.html 
5. Click "record" to capture your sound
6. Click "run" to start the sound
7. When you get enough of your sound recorded, click "stop," then click on "rec" again to stop the recording
8. Save your file as a .wav

# Hosting Sounds
9. Make a github account: github.com
10. Make a new repository
11. Initate with a "read me" file
12. Upload your wave file
13. "Commit" it
14. Click into the file and copy the url

# Using Our Hosted Sound in An Onclick Event
15. Add ```?raw=true``` to the end of your sound url 
16. Copy that whole url
17. Then add the url to the following bit of code (replace the URL already in the code with your own) 
18. Embed the code onto your own website, and enjoy a user feedback sound of your own creation!
  
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
