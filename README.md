skarf.js
========

### Introduction

This is a framework for handling JavaScript augmented reality (AR) libraries in Three.js.

### Integrated AR libraries

 * JSARToolKit
 * js-aruco

### Features

 * Specify marker-model relationships using a [JSON marker-model file](https://github.com/skeelogy/skarf.js/blob/master/examples/models/models_jsartoolkit.json). An internal marker manager automatically manages loading of models when associated marker is detected.
 * Model loader system to easily load different file formats (OBJ, JSON and binary JSON) into Three.js
 * All coordinate system differences between different AR libraries have been compensated to fit Three.js' right-handed Y-up coordinate system (i.e. no flipping, weird orientation of models etc)
 * Specified main marker defines the origin. Camera and other markers are all positioned relative to this origin.
 * GUI markers system that allows users to control user settings using AR markers
 * Expandable to fit other JavaScript AR libraries in the future

### Examples

* [Tracking Three.js Scene](http://skeelogy.github.io/skarf.js/examples/skarf_trackThreejsScene.html)

### Docs

* [1.0](http://skeelogy.github.io/skarf.js/docs/1.0)

### License

Released under GNU General Public License version 3 (GPLv3)<br/>
Copyright (c) 2013 Skeel Lee ([http://cg.skeelogy.com](http://cg.skeelogy.com)) @skeelogy