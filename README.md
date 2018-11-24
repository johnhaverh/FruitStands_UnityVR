# FruitStands_UnityVR

Combining VR and Gamification to create a module for my Senior Capstone Thesis

This module is a self-contained unit of an introductory computer science topic. The module practices the programming concepts of Lists and present them in a gamified VR application. The purpose of this module is to test whether it can improve the academic performance of introductory computer science students. The module was developed using Unity's free VR software, the Oculus Rift Virtual Reality Gaming System, and a Window's workstation.

I'm a complete novice at Unity and this project was implemented/programed in 2 months. Below I will describe different information about my final VR project.

## Table of Contents  
[Oculus Rift Setup](#oculus-rift-setup)

[Unity Environment Setup](#unity-environment-setup)

[Unity Assets Used](#unity-assets-used)

[Unity Scenes Created](#unity-scenes-created)

[Build Settings](#build-settings)

## Oculus Rift Setup

- In the oculus box, there is a small pamphlet that tells you to go to this website to help you get started (Took about 40 minutes to       download) : https://www.oculus.com/setup/
- If you need to access the Oculus Rift support website go to: https://support.oculus.com/
- Note: I used a Windows Desktop as my workstation. During my setup, I realized that the sensors couldn't be connected to the USB 3         connection in the back of the computer due to a known Oculus issue. One work around for this is to connected it to the USB port in the     front of the computer tower. If you are connecting another USB into the front of the computer, make sure you don't use the oculus at the   same time because it may cause issues with the oculus connection.
- The oculus headset can be connected to the HDMI and USB 3 connection without issue.

## Unity Environment Setup

- You can set up a free unity account and download the software from: https://store.unity.com/
- Once on the Unity main screen, create a new project and set it as 3D
- When the project loads go to: File > Build Settings > Player Settings > XR Settings. Once there set Virtual Reality Supported to on and   select Oculus.
- When starting you project you'll also need to go to: https://developer.oculus.com/downloads/unity/
- Download the following from the website above: 
  - Oculus Utilities for Unity
  - Oculus Avatar SDK
  - Oculus Platform SDK
- Once downloaded, drag their unity packages into the Assets folder in Unity and import them.
- A video explaining the above can be found here: https://www.youtube.com/watch?v=sxvKGVDmYfY

## Unity Assets Used

After you've downloaded and setup Unity and the Oculus Rift, you can download my FruitStand project from Github and add the desired assests to the assests folder of your newly created project. You may need to download some of the following Unity assets below to fully view my project:
  - Oculus Integration
  - VR Samples
  - TextMesh Pro
  - NavMeshController
  - Food & Grocery Items - Low Poly
  - Simple Shop Interiors - Cartoon assets
  - Character Pack: Free Sample
  - Free Voxel Girl (Dowloaded but ultimately not used)

## Unity Scenes Created

While developing my module, I created the following scenes:
  - Menu (*_Vrsn 1:_* A menu screen that was supposed to be used to load the final module select levels)
  - MainMenu (*_Vrsn 2:_* A menu screen that was supposed to be used to load the final module select levels)
  - VRCOntrols (Used for personal practice using Unity and the Oculus Rift)
  - TestingFood (Used to help participants practice using the Oculus Rift)
  - OpeningScene_Level1 and _Demo1 (Level 1)
  - OpeningScene_Level2 and _Demo2 (Level 2)
  - OpeningScene_Level3 and _Demo3 (Further levels that weren't fully implemented)
  - OpeningScene_Level4 and _Demo4 (Level 3)
  - _Demo5 (Further levels that weren't fully implemented)
  - Ending (The final screen shown to participants that used my module)

## Build Settings

When building my project, you must add the scenes in the proper cronological order to run the module. This can be done by going to: File > Build Settings and then selecting "Add Open Scenes." As you can already guess, this adds the open scene to the "Builds In Scene" list. To play my module you must add the scenes in the following order: 
  - OpeningScene_Level1 -> _Demo1 -> OpeningScene_Level2 -> _Demo2 -> OpeningScene_Level4 -> _Demo4

    
