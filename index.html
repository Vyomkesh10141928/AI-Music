song = "";
left = 0;
right = 0;
Rx = 0;
Ry = 0;
scorel = 0;
scorer = 0;




function preload() {
    song = loadSound("music.mp3");
}

function setup() {
   canvas = createCanvas(600, 500);
   canvas.center();
   
   video = createCapture(VIDEO);
   video.hide();
   poseNet = ml5.poseNet(video, modelLoaded);
   poseNet.on('pose', gotPoses);
}

function draw() {
 image(video, 0, 0, 600, 500);
 fill("#FF0000");
 stroke("#FF0000");
 

 if (scorer > 0.2) {
     circle(Rx, Ry, 20);
     if (Ry > 0 && Ry <= 100) {
         document.getElementById("speed").innerHTML = "Speed = 0.5x";
         song.rate(0.5);
     }
     if (Ry > 100 && Ry <= 200) {
        document.getElementById("speed").innerHTML = "Speed = 1x";
        song.rate(1);
    }
    if (Ry > 200 && Ry <= 300) {
        document.getElementById("speed").innerHTML = "Speed = 1.5x";
        song.rate(1.5);
    }
    if (Ry > 300 && Ry <= 400) {
        document.getElementById("speed").innerHTML = "Speed = 2x";
        song.rate(2);
    }
    if (Ry > 400 && Ry <= 500) {
        document.getElementById("speed").innerHTML = "Speed = 2.5x";
        song.rate(2.5);
    }
 }

 if (scorel > 0.2) {
     circle(left, right, 20);
     InNumberleftWristY = Number(right);
     remove_decimels = floor(InNumberleftWristY);
     volume  = remove_decimels/500;
     document.getElementById("volume").innerHTML = "Volume = " + volume;
     song.setVolume(volume);
 }
}

function play(){
    song.play();
    song.setVolume(1);
    song.rate(1);
}

function modelLoaded() {
    console.log("Posenet Loaded");
}

function gotPoses(results) {
    if (results.length > 0) {
        console.log(results);
        scorel = results[0].pose.keypoints[9].score;
        scorer = results[0].pose.keypoints[10].score;
        console.log("scoreRightWrist = " + scorer + "scoreLeftWrist = "+scorel);
        left = results[0].pose.leftWrist.x;
        right = results[0].pose.leftWrist.y;
        console.log("Left wrist x -"+left+"Left wrist y -"+right);
        Rx = results[0].pose.rightWrist.x;
        Ry = results[0].pose.rightWrist.y;
        console.log("Right wrist x -"+Rx+"Right wrist y -"+Ry);
    }
}