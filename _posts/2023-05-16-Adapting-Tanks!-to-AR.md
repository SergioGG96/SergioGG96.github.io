---
layout: post
title: "TANKS! AR"
subtitle: "Adapting the game TANKS! to AR"
date: 2023-05-16 00:45:00 -0400
background: '/img/posts/Adapting-Tanks!-to-AR/ARUnityManual.png'
icon: '/img/posts/Adapting-Tanks!-to-AR/tanks.JPG'
---

Augmented Reality (AR) has become a fascinating manifestation of the fusion between the digital and the real world.

An adaptation of the video game [Tanks!](https://assetstore.unity.com/packages/essentials/tutorial-projects/tanks-tutorial-46209) from Unite Training Day 2015 to AR has been made.

[AR Foundation](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@5.1/manual/index.html) in Unity has been used for this purpose, leveraging the native AR SDK of the platform. Unity also supports the [Google ARCore XR Plug-in](https://docs.unity3d.com/Packages/com.unity.xr.arcore@5.1/manual/index.html) on Android.

In an augmented reality scene using AR foundation, we need to include an AR Session (in XR -> AR Session) and an AR Session Origin (in XR -> AR Session Origin).

The function of the AR Session is to maintain the AR components within the application, with this we can pause, reset or reactivate the AR elements of the mobile phone.

AR Session Origin enables the positioning of the device in the world and transforms real-world elements into the unity scene. When we move in the real world, the unity scene starts to move the AR Camera.

<img src="/img/posts/Adapting-Tanks!-to-AR/ARCamera.JPG" alt="img" class="responsive-img" width="750" height="600"/>

We have some other tools from AR Foundation like:
- The AR Plane Manager which detects the planes in the real world and generates them in the unity scene.
- AR Point Cloud Manager detects points that confrom a cloud of points, they are intended to detect important spots in the world and adjust the position of the device.
- The MakeAppearOnPlane Script lets you instantiate a Prefab Object on the scene in a specific plane.

We will use all the level art of the game to be instantiated by MakeAppearOnPlane script.

<img src="/img/posts/Adapting-Tanks!-to-AR/LevelArt.JPG" alt="img" class="responsive-img" width="750" height="600"/>

Sliders are also added to the interface allowing to rotate and scale the game level.

<img src="/img/posts/Adapting-Tanks!-to-AR/ScaleAndRotationSliders.JPG" alt="img" class="responsive-img" width="750" height="600"/>

Some inputs have been added to work on Android mobiles. We will use them to move and shoot with the tank.

<img src="/img/posts/Adapting-Tanks!-to-AR/InputTanks.JPG" alt="img" class="responsive-img" width="750" height="600"/>

Here are some screenshots:

<img src="/img/posts/Adapting-Tanks!-to-AR/screenshot1AR.jpg" alt="img" class="responsive-img" width="750" height="600"/>

<img src="/img/posts/Adapting-Tanks!-to-AR/screenshot2AR.jpg" alt="img" class="responsive-img" width="750" height="600"/>

<img src="/img/posts/Adapting-Tanks!-to-AR/screenshot3AR.jpg" alt="img" class="responsive-img" width="750" height="600"/>
