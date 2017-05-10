# UnitySkidmarks

A basic skidmark system intended for vehicles.
Originally written for my game [Scraps](http://www.scrapsgame.com) but intended to be general-purpose.

UnitySkidmarks is loosely based on a script from an old official Unity car tutorial, but with improved performance and zero garbage generation.

This repository comes with an example scene built with Unity 5.6, using Unity 5 standard assets for the vehicle and terrain.

![Visualisation example.](https://raw.github.com/nition/UnitySkidmarks/master/skid.gif)

The **UnitySkidmarks** folder is the only content required to make the system work on its own.

**Skidmarks.cs** is the main controller script, and all skidmark-making objects in the scene should call it. You could turn this into a singleton for easier access.

**WheelSkid.cs** is an example script for what you might put on a wheel to generate skidmarks. In the example scene, each wheel on the car has a copy of this script.
