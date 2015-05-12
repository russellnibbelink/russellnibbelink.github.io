<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta content="stuff, to, help, search, engines, not" name="keywords">
<meta content="Live Filters" name="description">
<meta content="Display Webcam Stream" name="title">
<title>Display Webcam Stream</title>
  
<style>
.container {
    margin: 2px auto;
    width: 500px;
    height: 375px;
    border: 10px #333 solid;
    padding: 2px;
}
#videoElement, #canvasElement {
    width: 500px;
    height: 375px;
    background-color: #666;
    
}
</style>
</head>
  
<body>
<div class="container">
    <video id="videoElement" controls autoplay muted></video>
</div>
<div class="container">
    <canvas id="canvasElement"></canvas>
</div>
<script>
    //alert("this website captures video and microphone");
    //myWindow = window.open("", "myWindow", "width=200, height=100"); //open a new window
    //myWindow.close(); //close the opened windowthe current window
    //myWindow.moveTo(); //move the current window
    //myWindow.resizeTo(); //resize the current window
    video = document.querySelector("#videoElement");
    canvas = document.getElementById("canvasElement");
    context = canvas.getContext("2d");
    
    console.log(video);
    console.log(canvas);
    console.log(context);
    
    navigator.getUserMedia = navigator.getUserMedia || navigator.webkitGetUserMedia || navigator.mozGetUserMedia || navigator.msGetUserMedia || navigator.oGetUserMedia;

    window.requestAnimationFrame = window.requestAnimationFrame || window.msRequestAnimationFrame || window.mozRequestAnimationFrame || window.webkitRequestAnimationFrame;
    
    if (navigator.getUserMedia) {       
        navigator.getUserMedia({video: true, audio: true}, handleVideo, videoError);
    }

    function handleVideo(stream) {
        var source = window.URL.createObjectURL(stream);
        video.src = source;
        console.log("Webcam Active.");
        requestAnimationFrame(draw);
        
        //context.drawImage(video,0,0);
        //window.requestAnimationFrame(draw);
    }

    function videoError(e) {
        alert("video not working");
    }
    
    document.getElementById('canvasElement').onclick = function() { 
        context.drawImage(video,0,0, 300, 150);
    } 
    
    
    
    function draw() {
        context.drawImage(video,0,0, 300, 150);
        var img = context.getImageData(0, 0, 300, 150);
        var data = img.data;
        for (var i = 0; i < data.length; i+=4){
            var r = data[i];
            var g = data[i+1];
            var b = data[i+2];
            var avg = (r + g + b)/3;
            data[i] = avg;
            data[i+1] = avg;
            data[i+2] = avg;
        }
        context.putImageData(img,0,0); 
        //console.log(img.data.length);
        //console.log(img.data[0]);
        
        requestAnimationFrame(draw);
    }
    
  
</script>
</body>
</html>