## Webcam to Canvas with JavaScript using HTML5 
 
* Version 0.3 

## Important

This was a flash-based library with JS interoperability — this was a work not in progress in past 3 years. Now we have WebRTC and we should go the web way. The reason this is update is so that we can continue to evolve camera works — to ensure we have awareness of the importance for client side operations with camera. 

## Hall of Fame for Camera to JS 

Send your links – with this API or if you are using other APIs too. It's just a bit of code to add camera with WebRTC so let's think that this repo is more like a place to talk about, to learn, to be inspired and to action. 

## Legacy 0.2 with Flash (documentation)

Webcam to Canvas JavaScript API 0.2
===
This API allows you to capture webcam images and use it in the canvas tag to do whatever you like. This version depends on a flash-based SWF file. The .as source is also part of this project and can be compiled with Mtasc. You can also simply use the less than 5K swf binary. This is a client side library and once you have the webcam image in the canvas, you can do anything. 

Online Projects using CamCanvas and Demos
====
http://remixpic.taboca.com/co/mozilla/
http://cam.mamulti.com/ ( Bruno Barreto Face Detection Algorithm ) 
http://www.taboca.com/p/camcanvas/

Roadmap
====

* PENDING= Cam Gestures - higher level edge/pattern detection
* More image manipulation samples ( eliminate background, chromakey etc ) 

If you want to compile the as and change the SWF 
===

Mtasc - http://www.mtasc.org/#download 
SwfMill - http://swfmill.org/
Put mtasc and swfmill binary in this directory and use the build script. 
You will also need ./lib/* from mtasc : ./lib/std and ./lib/std8
./build.sh
Cp the binary ./swf/* to the ./samples/ and enjoy the samples. 

Release Notes
===

* 0.2
 + ccList function returns strings of camera names separated by comma
 + ccInit(index) 
 + ccCapture() works as the same

* 0.1 - basic function ccCapture() only;  Default was 320x240; Once the flash is active the webcam was initialized; expected JS callback needs to be called passLine. A line of 320 pixels is tranfered to JavaScript - all pixels in a string; 

