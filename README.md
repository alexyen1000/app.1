<p align="center">
<img src="/couchbase-logo-1.png" class="logo">
</p>

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html) [![Docs](https://img.shields.io/badge/docs-online-orange.svg)](http://cesiumjs.org/tutorials.html)

This application displays the information from the Couchbase server, plotting vertical lines on a globe to see the information based on location. It runs using [Cesium](http://cesiumjs.org/), which is a Javascript library for creating 3D globes and maps in a browser by using WebGL.  

The default settings show the number of times a unique cluster givin its location, version, and other factors had been accessed by customers. Note that the scale between lines are not linear as to keep the spectrum of line size within practical limits.

### Get Started ###

1. Make sure to download [Node.js](https://nodejs.org/en/) and then extract the latest Cesium version [here](https://cesiumjs.org/downloads.html).

2. Go to your terminal and run: $ npm install

3. To launch the server, run: $ node server.js

4. Launch a browser and go to this address: http://localhost:8080/Apps/PhoneHome.html

### Features ###

The application displays an interactive globe that shows the location of customer data points. Clicking on one of the points will show more information about the selected location. These include:

Version

Nodes

Location

IP Address

Times Accessed (Count)

The right hand panel shows global statistics, allowing a quick understanding of worldwide presence. Also found here is a dropdown menu to change the information that the lines represent. This can be toggled to N1QL, KV, and Index services apart from the default Count. There is also a resize function.

Some graphics toggles are also available, these being the day/night cycle and the rotating globe.

Some functions are built into Cesium, which can be used to change the globe into a 2D or 2.5D map, change the map texture, and bring the camera back to its original position. These are found on the globe's window.


### Mission ###

Our mission is to create an easy to read visual representation of data so that employees of Couchbase can better understand  customer presence and usesage of Couchbase's products. 

### License ###

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).  Cesium is free for both commercial and non-commercial use.

We appreciate attribution by including the Cesium logo and link in your app.

### Screenshot ###

<img src="/project-screenshot.png" class="logo">


