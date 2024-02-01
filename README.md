<!DOCTYPE html>
<html>
    <title>OCE</title>
    <body>
        <h1>Test JVS</h1>
        <p id ="test">Test JVS change text</p>
        <button type ="button" onclick='document.getElementById("test").innerHTML = "Text has been changed"'>Click to change</button>
        <button type="button" onclick="document.getElementById('test').style.fontSize='30px'">Change font size</button>
        <button type="button" onclick="document.getElementById('test').style.display='none'">Hide the text</button>
        <br><br>
        <p id="test1" style="display: none">Huraaa!</p>
        <button type="button" onclick="document.getElementById('test1').style.display='block'">Show the text</button>
        <br><br>
        <img id="img" src="C:\Users\Nam\Pictures\OLDPHOTOS\img1.jpg" alt="Truong hoc" width="640" height="480">
        <br><br>
        <button type ="button" onclick='document.getElementById("img").src="C:\Users\Nam\Pictures\OLDPHOTOS\img2.jpg"'>Change the picture</button>
        <button type="button" onclick='document.getElementById("img").src="C:\Users\Nam\Pictures\OLDPHOTOS\img1.jpg"'>Rechange the picture</button>
    </body>
</html>
