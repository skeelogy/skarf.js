skarf.js
========

### Introduction

This is a framework for handling JavaScript augmented reality (AR) libraries in Three.js.

### Integrated AR libraries

* JSARToolKit
* js-aruco

### Features

* Automatic loading of models when the associated markers are detected (association is specified in a JSON file). Currently supported model formats: .obj, .js and binary .js.
* Fixing of the world origin to a specified main marker, with the camera and other markers positioned around this origin for lighting/shadows to work properly in the 3D scene
* Automatic compensation for coordinate system differences between the different AR libraries and Three.js (which might otherwise lead to flipping and offsetted orientations of loaded models)
* GUI marker system which allows users to control settings using AR markers
* Expandable to fit other JavaScript AR libraries in the future

### Examples

**1) Tracking Three.js Scene** [[Demo](http://skeelogy.github.io/skarf.js/examples/skarf_trackThreejsScene.html)]

&nbsp;&nbsp;&nbsp;[![ScreenShot](http://skeelogy.github.io/skarf.js/screenshots/video_skarf_trackThreejsScene.jpg)](http://www.youtube.com/watch?v=FjjuFBcg0_Y)

* Tracking of a Three.js 3D scene to prevent webcam problems such as motion blur and lens distortion (for testing purposes)
* Loading of models when associated markers are detected

**2) HTML5 Augmented Reality Interactive Flood Simulation** [[Demo](http://skeelogy.github.io/ifc-ar-flood/demo.html)]

&nbsp;&nbsp;&nbsp;[![ScreenShot](http://skeelogy.github.io/ifc-ar-flood/screenshots/video_ifcArFlood_main.jpg)](http://www.youtube.com/watch?v=qEFH_r_X7kY)

* Tracking of webcam video stream
* Using GUI markers system to control user settings with AR markers
* Loading of models when associated markers are detected
* Usage of main marker to define origin

### Docs

* [1.0.x](http://skeelogy.github.io/skarf.js/docs/1.0.x)

### License

Released under GNU General Public License version 3 (GPLv3)<br/>
Copyright (c) 2013 Skeel Lee ([http://cg.skeelogy.com](http://cg.skeelogy.com))
