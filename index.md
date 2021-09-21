# Roland Bruggmann — Portfolio

<!-- Start Document Outline -->

* [1. Unreal Engine Projects](#1-unreal-engine-projects)
	* [1.1. Distributed Real-Time Rendering in Sensorimotor Laboratory](#11-distributed-real-time-rendering-in-sensorimotor-laboratory)
		* [1.1.1. Short Summary](#111-short-summary)
		* [1.1.2. Documentation](#112-documentation)
		* [1.1.3. External References](#113-external-references)
	* [1.2. Modelling and Animation of 3D Objects for Use in a Dream-Like Virtual Environment](#12-modelling-and-animation-of-3d-objects-for-use-in-a-dream-like-virtual-environment)
		* [1.2.1. Short Summary](#121-short-summary)
		* [1.2.2. Documentation](#122-documentation)
		* [1.2.3. External References](#123-external-references)
* [2. Unity® Projects](#2-unity-projects)
	* [2.1. Unity® Volume Rendering — Plug-in for 3D-Rendering of Medical Data](#21-unity-volume-rendering--plug-in-for-3d-rendering-of-medical-data)
		* [2.1.1. Short Summary](#211-short-summary)
		* [2.1.2. External References](#212-external-references)
	* [2.1. Rigged Body Animation in Unity®](#21-rigged-body-animation-in-unity)
		* [2.2.1. Short Summary](#221-short-summary)
		* [2.2.2. External References](#222-external-references)

<!-- End Document Outline -->

## 1. Unreal Engine Projects

### 1.1. Distributed Real-Time Rendering in Sensorimotor Laboratory

August 2019 - June 2021, Technology Platform for Research approved project "Distributed Game Engine DGE" aka "UE4 Display Cluster in CAVE" and subsequent projects at Faculty of Human Sciences on behalf of Prof. Dr. Ernst-Joachim Hossner, Institute of Sport Science ISPW, Department of Movement and Exercise Science at University of Bern.

![Projection of an Unreal Engine 3D-Scene in Sensorimotor Laboratory CAVE.](TeaserSensorimotorLab-3DRendering-CAVE.jpg "Projection of an Unreal Engine 3D-Scene in Sensorimotor Laboratory CAVE.")
<p><em>Fig. 1.1.: Projection of an Unreal Engine 3D-Scene in Sensorimotor Laboratory CAVE.</em></p>

#### 1.1.1. Short Summary

An Unreal Engine project based on the display cluster template "nDisplay" providing game-levels related to the Institute of Sports Science ISPW at University of Bern, more precisely for the sensorimotor lab of the institute with its five-sided CAVE. The lab integration is enabled by a newly developed messaging layer that is used to interact with an Enterprise Service Bus ESB. Custom-developed Unreal Engine plugins are used to control VR objects via the lab's experiment management system and render 360° videos and CAVE-specific 3D content. Due to the plugin-based architecture, the integration solution is modular and can also be used in other laboratories of the faculty.

![Screenshot of an Ice Hockey Scene as 360° Spherical Video Playback in Unreal Editor.](TeaserSensorimotorLab-360DegVideo-UnrealEditor.jpg "Screenshot of an Ice Hockey Scene as 360° Spherical Video Playback in Unreal Editor.")
<p><em>Fig. 1.2.: Screenshot of a 360° Spherical Video Playback Ice Hockey Scene in Unreal Editor.</em></p>

![The same Ice Hockey Scene as Unreal Engine 360° Spherical Video Playback in Sensorimotor Laboratory CAVE.](TeaserSensorimotorLab-360DegVideo-CAVE.jpg "The same Ice Hockey Scene as Unreal Engine 360° Spherical Video Playback in Sensorimotor Laboratory CAVE.")
<p><em>Fig. 1.3.: Projection of the same 360° Video in the Sensorimotor Laboratory CAVE using Unreal Engine.</em></p>

#### 1.1.2. Documentation

* [UE Display Cluster Project "Sensorimotor Lab"](SensorimotorLab)
* [Integration Testing by Jupyter Notebook as ESB Messaging Endpoint](ISPW/Testing/)

For these plugins, only the documentation is publicly available:

* [Blueprint Plugin "Play Area"](PlayArea)
* [Blueprint Plugin "Immersive Video"](ImmersiveVideo)
* [Blueprint Plugin "Sports Equipment"](SportsEquipment)
* [Blueprint Plugin "AprilTag Images"](AprilTagImages)
* [Code Plugin "Pupil Core"](Pupil)
* [Code Plugin "ZeroMQ"](ZeroMQ)
* [Code Plugin "ESB Messaging"](ESBMessaging)
* [Code Plugin "Distributed Game Engine DGE"](DGE)
* [Blueprint Plugin "Institute of Sport Science ISPW"](ISPW)

#### 1.1.3. External References

* [*UE Display Cluster in CAVE*](https://www.tpf.philhum.unibe.ch/portfolio/ue4DisplayCluster), In: Online-Portfolio of Technology Platform for Research TPF, Faculty of Human Sciences, University of Bern
* TPF Project Report (pdf) on Slide Share: https://www.slideshare.net/secret/lROZ8b2qfVbkso
* [*Der Blick von Topathletinnen wird optimiert*](https://www.horizonte-magazin.ch/2021/09/02/einblick-in-den-blick-von-topathletinnen/), In: Horizonte - Das Schweizer Forschungsmagazin (Online), Santina Russe, 02. September 2021

### 1.2. Modelling and Animation of 3D Objects for Use in a Dream-Like Virtual Environment

January-July 2019, Technology Platform for Research approved project "3D Content for Dream-Like VR" at Faculty of Human Sciences on behalf of Prof. Dr. Fred Mast, Institute of Psychology, Department of Cognitive Psychology, Perception and Research Methods at University of Bern.

![Virtual Twin of the Dream Simulation Lab in Unreal Editor.](TeaserDreamSimLab.jpg "Virtual Twin of the Dream Simulation Lab in Unreal Editor.")
<p><em>Fig. 1.4.: Virtual Twin of the Dream Simulation Lab in Unreal Editor.</em></p>

#### 1.2.1. Short Summary

Experience of reality is highly flexible and unstable. This becomes apparent during the wake-sleep cycle when dreams appear real to us. To investigate alterations in the experience of reality and its underlying mechanism, a bizarre virtual environment is used to elicit altered experiences. Therefore, 3D objects and environments had to be created.

#### 1.2.2. Documentation

* [UE Virtual Reality Project "Dream Simulation Lab"](DreamSimLab)
* [Code Plugin "Bizarre BZR"](BZR)
<!-- * [Content Plugin "Virtual Learning Attendance VIRLA"](VIRLA) -->

For this plugin, only the documentation is publicly available.

#### 1.2.3. External References

* [*3D Content for Dream-Like VR*](https://www.tpf.philhum.unibe.ch/portfolio/dreamLikeVR), In: Online-Portfolio of Technology Platform for Research TPF, Faculty of Human Sciences, University of Bern
* TPF Project Report (pdf) on Slide Share: https://www.slideshare.net/secret/lUQIwIEFTZYEq
* [*Le pouvoir de l'imaginaire*](https://www.rts.ch/play/tv/redirect/detail/12161998?startTime=358), RTS Radio Télevision Suisse , 01.05.2021 (video playback start time 5:58)

## 2. Unity® Projects

### 2.1. Unity® Volume Rendering — Plug-in for 3D-Rendering of Medical Data

January-June 2016, Institute for Human Centered Engineering HuCE, Laboratory for Computer Perception and Virtual Reality, Bern University of Applied Sciences BUAS.

![Real-Time Rendering of a Neurovascular Angiography in Unity Editor.](TeaserVolumeRendering.jpg "Real-Time Rendering of a Neurovascular Angiography in Unity Editor.")
<p><em>Fig. 2.1.: Real-Time Rendering of a Neurovascular Angiography in the Unity® Editor.</em></p>

#### 2.1.1. Short Summary

In the context of my Bachelor's Thesis I implemented a Unity® plug-in for 3D visualisation of MRI/CT data which can be used in VR/AR applications. Therefore I wrote a raycaster pixel-shader running on GPUs.

#### 2.1.2. External References

* [*Unity® Volume Rendering—Plug-in for Rendering of Medical Data*](https://www.linkedin.com/pulse/unity-volume-rendering-roland-bruggmann/), Roland Bruggmann, In: LinkedIn.

### 2.1. Rigged Body Animation in Unity®

November – December 2018, Technology Platform for Research approved project "3D Workflow" aka "Rigged Body Animation in Unity" at Faculty of Human Sciences on behalf of Prof. Dr. Ernst-Joachim Hossner, Institute of Sport Science ISPW, Department of Movement and Exercise Science at University of Bern.

![Real-time Animation of Rigged Avatar by Motion Capture in Sensorimotor Lab.](TeaserRiggedBodyAnimation.jpg "Real-time Animation of Rigged Avatar by Motion Capture in Sensorimotor Lab.")
<p><em>Fig. 2.2.: Real-time Animation of Rigged Avatar by Motion Capture in Sensorimotor Lab.</em></p>

#### 2.2.1. Short Summary

3D Content Generation and Interactive Real-Time Animation of Rigged Avatar by Motion Capture in Sensorimotor Laboratory

* Index Terms: Virtual Reality, 3D Modelling, Rigging, Motion Capture, Real-time Animation
* Technology: Blender, MakeHuman, Unity Game Engine, OptiTrack, Power-Wall

#### 2.2.2. External References

* [*Rigged Body Animation in Unity®*](https://www.tpf.philhum.unibe.ch/portfolio/RiggedBodyAnimation), In: Online-Portfolio of Technology Platform for Research TPF, Faculty of Human Sciences, University of Bern
