Smol Satellites
=================

This is a fork of the original project, [Satellite Tracker](https://github.com/dsuarezv/satellite-tracker) by [David Suarez](https://github.com/dsuarezv), to focus on interacting with small satellites with AWS Ground Station.

Technologies include [Three.js](https://threejs.org/), [React](https://reactjs.org/), [satellite.js](https://github.com/shashwatak/satellite-js), and [AWS Ground Station](https://aws.amazon.com/ground-station/).

I referenced [this map](https://docs.aws.amazon.com/ground-station/latest/ug/aws-ground-station-antenna-locations.html) from AWS Documentation: 
![AWS Ground Station Antenna Locations](/screenshots/antenna-locations.png)

Next, I used [CelesTrack](https://celestrak.org/), a 501(c)(3) non-profit to search for small satellites and their [TLEs](https://celestrak.com/NORAD/elements/) for [CubeSats](https://celestrak.com/NORAD/elements/cubesat.txt) and [MicroSats](https://celestrak.com/NORAD/elements/microsat.txt).

While unfortunately incomplete, the next objective was to implement functionality for finding the nearest eligible [AWS Ground Station](https://aws.amazon.com/ground-station/) to selected satellites. This would allow researchers and the general public to schedule command and control operations, as well as downlink and display instrument data. 

Installation
============

    $ git clone https://github.com/jefferyjohn/smol-satellites
    $ cd satellite-tracker
    $ npm install
    $ npm start