---
title: How to Work with a Tracked Scene
sidebar_position: 1
---

1\. When you run a new project, the user interface is displayed by default in the Trigger module.

1. Note that it appears empty, which means that no scenes have been created in the Qimera project so far.
2. To create a new scene, go to the composition module

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-25/449941f0-a3e1-472f-804a-bb2c614cfcc0/user_cropped_screenshot.webp?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=-10,103)


2\. This panel appears only for the first scene in your project; after that, you can create scenes directly from the Scene Selection Panel.

In this panel you can select the type of scene you want, Trackless Scene or Tracked Scene.

Then select Tracked Scene

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-21/c0e466e0-c00b-4b68-a5c1-d88cda7e6f18/ascreenshot.jpeg?tl_px=334,239&br_px=1710,1008&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=703,311)


3\. At this point you are in the Composition module, this is where you will create the composition of the scene *([Understanding the composition module](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/QuickStart/CreatingScene))*

By default Tracked scene is the name of the new scene previously created, you can create a New Scene with your custom name by clicking in the plus icon.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/353604d6-a560-440e-acc8-2dceb66406f0/user_cropped_screenshot.webp?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


4\. Once the panel appears you will see these 3 fields

1. Scene Name: You can type any name you like. Lets add Scene Cam1 as example.
2. Keep Saves: Here you can decide whether you want to have default values for the new scene leaving the dot on the left (Switch in OFF mode) or copy all the data from the current scene to the new one leaving the dot on the right (Switch in ON Mode). Lets Keep saves Off as example
3. Confirm to create the new scene

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/8514829f-7209-4d1e-a4fb-be4d5674dd2b/user_cropped_screenshot.webp?tl_px=0,47&br_px=662,419&force_format=jpeg&q=100&width=667&wat_scale=59&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=421,182)


5\. Then open The Scene Selection List and select the new scene

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-22/87389ef4-d695-4a58-a827-3a1f4ece0cd7/ascreenshot.jpeg?tl_px=1294,49&br_px=1919,398&force_format=jpeg&q=100&width=625&wat_scale=55&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=317,152)


6\. At this point we have created a new scene with a custom name and default values.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/01ec415d-ae79-49c5-9b49-9c2d0d2da11e/user_cropped_screenshot.webp?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


7\. There 4 elements that you need to connect in order to have a correct Tracked Scene Composition

- Camera Feed: Link the video signal coming from the real camera with the new scene
- Tracker System: Link the preset containing all the data from the tracker connected to the real camera with the new scene
- Coordinates: Link the preset that contains the coordinate in the virtual world with the new scene
- Garbage Matte: Link Matte preset that contains all date related to matte with the new scene.

In the following steps we will delve one by one into these elements.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-25/30f043aa-3c3f-4915-a63d-5e79549d69c0/screenshot.webp?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


8\. Lets start with Camera Feed

1. First Make sure the eye of the layer is On
2. Click on the center of the thumbnail
3. Next, notice that on the right panel you will have all the details of the camera feed layer. [(Understanding Camera Feed Layer)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/QuickStart/CreatingScene)

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/23d44031-0862-474e-983c-11ed6727b6e4/user_cropped_screenshot.webp?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


9\. Let's dive into the details of the camera feed layer.

1. Click the "Media Input" panel to open it.
2. Make sure the "Media Input" feature is enabled.
3. Click on the "Media Texture Input" list to see the available SDI inputs. [(How to Add SDI inputs to Qimera)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/Triggers/Trigger-Types)
4. You can find the SDI input name directly by typing it or selecting it from the list.
5. Select the SDI input. In this example, we'll select SDITexture-1

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/cb3cd481-cd77-4ff8-a521-2fec198cb509/user_cropped_screenshot.webp?tl_px=870,33&br_px=1920,619&force_format=jpeg&q=100&width=1049)


10\. Now, let's go to the Chroma Key settings panel.

In Qimera, we can have different Chroma Keys associated with different scenes.

1. Open Chorma Key Setting panel
2. Select which slot you going to use for you key parameters. for this example let's use Key 1.
3. Save the slot

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/6c1d7ed4-72f5-4e9b-b571-9bae49e9b691/user_cropped_screenshot.webp?tl_px=853,168&br_px=1713,649&force_format=jpeg&q=100&width=860)


11\. Next is Chroma Key Parameters panel

Here you can choose the color for your key and tune it. [(How to Set and Tune Chorma key on Qimera)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/QuickStart/CreatingScene)

1. Open Chroma Key Parameters panel.
2. Switch On Chroma Feature
3. Switch On Despill option
4. Save

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/6f498135-dc16-4000-b153-fc1737d1c8d3/user_cropped_screenshot.webp?tl_px=937,167&br_px=1920,716&force_format=jpeg&q=100&width=983)


12\. At this point you can see how the background and camera feed layer are combined in the composition monitor.

Note: The BG view may not be aligned with the horizon or may be in the wrong position. This is because you are not setting the camera tracking preset at this point.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/5ba0097b-0876-4fb8-9a7b-5aae176940e3/user_cropped_screenshot.webp?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


13\. Now lets connect you tracking data with the scene

Click in the small gear next to the Virtual Camera selector

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-22/4f44fc7f-44b9-4698-8e6a-72aa61f3f8df/ascreenshot.jpeg?tl_px=773,0&br_px=1920,640&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=570,108)


14\. Please note that the calibration module opens specifically in the camera tracking settings panel. [(Understanding Calibration Module)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/QuickStart/CreatingScene)

Here you going to select the Tracking preset accordingly with you tracker input[(How to create a Tracking Preset)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/QuickStart/CreatingScene)

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/2c10c868-1107-486a-b16b-065127b27b3d/user_cropped_screenshot.webp?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


15\. 1. Go to Tracking Preset and open the list
2. select the preset accordingly with you Camera Tracking System
3. Click in Load

[(How to create a Tracking Preset)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/QuickStart/CreatingScene)

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-28/6bd6b32d-8335-439e-8f33-6b3f3d92c994/user_cropped_screenshot.webp?tl_px=1155,81&br_px=1920,509&force_format=jpeg&q=100&width=764)


16\. In this case, preset 1 shows that the tracker selection is Camera 0, which is the tracker ID that Unreal receives via the live link from the tracker system connected to the real camera. [(How to connect tracker Data to Livelink)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/QuickStart/CreatingScene)

Additionally, the preset contains the lens file corresponding to your actual camera lens. [(How to create a Lens File)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/QuickStart/CreatingScene)

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-26/90d8faca-df46-4ba3-8b74-eecdb51b21a3/user_cropped_screenshot.webp?tl_px=937,242&br_px=1920,791&force_format=jpeg&q=100&width=983)


17\. Then close The calibration Module

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-22/9c759d23-23c6-46ef-8669-c215536471d0/ascreenshot.jpeg?tl_px=544,163&br_px=1920,932&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=612,277)


18\. Now Let's dive in into Matte or Mask layer setup (Garbage Matte).

1. Click the center of the purple thumbnail next to the camera thumbnail.
2. Notice that a matte layer details panel appears on the right. Make sure that, in the "Augmented Reality Elements" section, the matte element is included in the layer [(How to include and exclude AR elements in a layer)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/intro)
3. Open the matte settings panel by clicking the gear.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-28/612fa0ae-019c-4486-943c-688add4da6ac/user_cropped_screenshot.webp?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


19\. Please note that the calibration module opens specifically in the Matte settings panel.

In this panel, you need to select the Matte Preset that best suits your scene.

The Matte is typically a virtual representation of the green screen used to hide all elements outside the green screen from the actual video signal.\
(How to create a Matte Preset)

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-29/b66ec0c6-e58a-4864-9d25-05ff4b3f0033/user_cropped_screenshot.webp?tl_px=773,439&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


20\. 1. Select your preset
2. then click Load
3. Close The Calibration Module

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-29/96fb903a-f721-4be4-8a28-6232ec6fb684/user_cropped_screenshot.webp?tl_px=0,310&br_px=814,1080&force_format=jpeg&q=100&width=1120.0)


21\. Notice in the Compositing Monitor that the outer portion of the green screen is still visible at this point. This is because there are still two very important steps remaining.

1. Enable Matte Layer
2. Invert the mask

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-29/b455f9fa-6b45-4b69-b0c2-b6628a9bb853/user_cropped_screenshot.webp?tl_px=0,0&br_px=1221,1020&force_format=jpeg&q=100&width=1120.0)


22\. Now you can see in the Composition monitor how the matte covers the outside of the green wall (Garbage Matte)

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-29/2441d43d-9a81-4232-b10c-23088b8e810c/user_cropped_screenshot.webp?tl_px=100,59&br_px=1820,1020&force_format=jpeg&q=100&width=1120.0)


23\. Now lets set the coordinates of the virtual world to the scene

1. Double click in Calibration Module.
2. Click on Placement Settings to open the panel.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-29/1d27cb03-e2f8-4bd7-b89c-d365437e3923/user_cropped_screenshot.webp?tl_px=0,0&br_px=1919,561&force_format=jpeg&q=100&width=1120.0)


24\. 1. Open Placement Preset list
2. Select the preset that you need for you scene, in this case we going to select "Office" [(How to create a Placement Preset)](https://cautious-broccoli-rw1kn8j.pages.github.io/docs/category/tracked-workflow)
3. Click on Load
4. Close the Calibration Module

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-29/7e5f9eea-5efb-4c26-bf10-86c7eb9d5171/user_cropped_screenshot.webp?tl_px=0,0&br_px=902,639&force_format=jpeg&q=100&width=1120.0)


25\. At this point you have already connected the four basic elements in your New Scene

Camera Feed\
Track System\
Coordinates\
Garbage Matte

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-07-22/380ee26a-2c5d-47b9-b869-a87c14181cf5/ascreenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=-14,267)


26\. You can select yours scene already created into the Scene Selections panel.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-02/cf50d2d4-f640-4fa0-9999-41824f1519a4/user_cropped_screenshot.webp?tl_px=0,0&br_px=1806,1008&force_format=jpeg&q=100&width=1120.0)


27\. Or you can go to the Trigger module and switch between scenes for convenience.

1. Click on Trigger Modules Icon
2. Check the scenes that you have created so far into the Switch Scenes panel
3. Click in the Left side of the Thumbnail of the scene that want to activate

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-02/8313c1ef-6be9-4049-b103-7d97c0f02535/user_cropped_screenshot.webp?tl_px=0,384&br_px=1238,1076&force_format=jpeg&q=100&width=1120.0)


28\. Please note that when you switch to another scene, you will have the last frame of the previous scene in the thumbnail of the previous scene.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-02/13f92aad-e148-4e1f-aa34-95c00d85753d/user_cropped_screenshot.webp?tl_px=0,245&br_px=1188,910&force_format=jpeg&q=100&width=1120.0)


29\. To Delete an scene

1. Select the scene you want to delete
2. Go to Composition Module

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-02/7bd6d792-1f6c-4cf7-ab67-973c7418387f/user_cropped_screenshot.webp?tl_px=0,103&br_px=1191,769&force_format=jpeg&q=100&width=1120.0)


30\. 1. Make sure you have selected the scene you want to delete.
2. Click the X icon.
3. A warning panel will appear; click Confirm.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-02/1bd04224-899d-4449-a690-a1b577da2bb2/user_cropped_screenshot.webp?tl_px=1100,0&br_px=1804,393&force_format=jpeg&q=100&width=704)


31\. If you check the list, the scene you deleted no longer appears.

**NOTE: Deleted scenes cannot be recovered**

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-02/2a5dedba-bab3-48f8-a6bd-e2737bf65637/screenshot.webp?tl_px=0,0&br_px=577,539&force_format=jpeg&q=100&width=966)


32\. Before we move on to creating another scene, let's take some final steps for this particular scene.

1. Click on the Composition module.
2. Make sure you have the desired scene selected.
3. Click on the Compositing Monitor.
4. You will see the Compositing Details panel, where you can select and adjust features related to the final output of your scene.
5. One of these is the Post-Processing Selection feature: this feature allows you to make adjustments to color correction, exposure, and very important rendering-related features, such as lumen capacity and ray tracing options.
6. Another important feature is the SDI Output feature. This is where you will activate your scene's output.

Next we will focus on post-processing and SDI output.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-02/c2819055-7d10-4ea0-a611-a391789556b9/user_cropped_screenshot.webp?tl_px=0,0&br_px=1802,1015&force_format=jpeg&q=100&width=1120.0)


33\. If you open the Post Process Selection list and this is empty, that mean that theres not a post process volume in this map or level

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-02/bdab1551-38ab-4c51-9a61-1ba1cf1eebad/user_cropped_screenshot.webp?tl_px=0,0&br_px=978,668&force_format=jpeg&q=100&width=1120.0)


34\. 1. Press F11
2. Press Escape to close the Qimera Session and go back to the unreal editor.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-02/33df20f1-e588-420a-9cbb-5e0f8ff90cc9/screenshot.webp?tl_px=0,0&br_px=1800,1017&force_format=jpeg&q=100&width=1120.0)


35\. 1. Click on the "Quickly add to the project" button.
2. Go to "Volumes".
3. Select Post Process Volume option.
4. Launch Qimera.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-04/27d674ed-e3a7-4829-a55b-df04cccf26b3/user_cropped_screenshot.webp?tl_px=0,0&br_px=1801,965&force_format=jpeg&q=100&width=1120.0)


36\. 1. Click on the Qimera UI
2. Press F11 to maximize Qimera UI

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-04/61430437-e093-4606-a2e7-cb25b5fec948/user_cropped_screenshot.webp?tl_px=0,0&br_px=1807,1015&force_format=jpeg&q=100&width=1120.0)


37\. 1. Click on Composition Module
2.

![](https://ajeuwbhvhr.cloudimg.io/https://colony-recorder.s3.amazonaws.com/files/2025-08-04/527e4ddc-7ff9-404e-866b-4607bf902528/user_cropped_screenshot.webp?tl_px=0,0&br_px=1802,1016&force_format=jpeg&q=100&width=1120.0)

