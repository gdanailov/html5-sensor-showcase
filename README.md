html5-sensor-showcase
=====================

This repository contains a simple showcase html page. It is a demonstration of the various ways a website can retrieve data from the sensors of a browser's host device.

The html5 features that power this is still relatively new, and currently (Nov 2013) Chrome, Firefox, and Opera are the only browsers that supports all the showcased features.

<h2>Video and Camera</h2>
The first row demonstrates HTML5's getUserMedia(), which allows the browser to retrieve camera and microphone data. Some browser versions even allow the user to chose which camera to use. Video is simply filtered playback, but due to the potential for feedback, the microphone is not.

<h2>Position and Orientation</h2>
The second row demonstrates methods to get device location and orientation. A mobile browser is more likely to see the full feature set, as they tend to have GPS and accelerometers built in.

<h2>Camera and Microphone Form Fields</h2>
The last row demonstrates an extension to the file upload form field. This generally only works for mobile devices. By specifying the desired file type, users can provide files created through the camera or microphone.