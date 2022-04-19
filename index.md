
[<< Back to *https://about.me/rbruggmann*](https://about.me/rbruggmann)

# Unity and Unreal Game Engine Projects and Plugins

## Document Outline
<!-- Start Document Outline -->

* [1. Unity Volume Rendering](#1-unity-volume-rendering)
* [2. Unity Solar System](#2-unity-solar-system)
* [3. Unity Rigged Body Animation](#3-unity-rigged-body-animation)
* [4. UE4 Content for Dream-like VR](#4-ue4-content-for-dream-like-vr)
* [5. UE4 Display Cluster in CAVE](#5-ue4-display-cluster-in-cave)
* [6. UE Plugin: Integration Tool](#6-ue-plugin-integration-tool)
* [A. Unreal Online Learning: Achievements](#a-unreal-online-learning-achievements)

<!-- End Document Outline -->

# 1. Unity Volume Rendering

![Real-time Rendering of a Neurovascular Angiography in Unity Editor.](TeaserVolumeRendering.jpg "Real-time Rendering of a Neurovascular Angiography in Unity Editor.")
<p><em>Fig. 1.: Real-time Rendering of a Neurovascular Angiography in the Unity® Editor.</em></p>

## 1.1. Short Summary

*Plug-in for Rendering of Medical Data*

In the context of my Bachelor's Thesis I implemented a Unity® plug-in for 3D-rendering of medical data (MRI/CT) which can be used in VR/AR applications. Therefore I wrote an efficient raycaster pixel-shader running on GPUs.

* **Index Terms:** Medical Imaging, Real-time Rendering, Raycasting, GPU Programming, Virtual Reality
* **Technology:** Unity® Game Engine, .NET/C#, JSON, Cg/HLSL, VTK, DICOM

January-June 2016, Institute for Human Centered Engineering HuCE, Laboratory for Computer Perception and Virtual Reality, Bern University of Applied Sciences BUAS

## 1.2. External References

* Bachelor's Thesis:
  * <a href="https://bfh.easydocmaker.ch/search/abstract/1201/" target="_blank">Abstract</a> on EasyDocmaker
  * <a href="https://www.slideshare.net/RolandBruggmann/unity-volume-rendering-poster" target="_blank">Poster</a>, and <a href="https://www.slideshare.net/RolandBruggmann/unity-volume-rendering" target="_blank">Presentation</a> on SlideShare
  * <a href="https://www.youtube.com/watch?v=-dfjpM1qk3I" target="_blank">Screencast</a> on YouTube
* Article <a href="https://www.linkedin.com/pulse/unity-volume-rendering-roland-bruggmann/" target="_blank">*Unity® Volume Rendering*</a>, Roland Bruggmann on LinkedIn

---

# 2. Unity Solar System

![3D Solar System in Unity Editor.](TeaserSolarSystem.jpg "3D Solar System in Unity Editor.")
<p><em>Fig. 2.: 3D Solar System in the Unity® Editor.</em></p>

## 2.1. Short Summary

3D Solar System Simulator as Demo of C#-Scripts Toolset *RotateAroundTarget* - *Rotation*, *Revolution*, *Look at Target*.

* **Index Terms:** 3D Solar System Simulator, Texture Mapping
* **Technology:** Unity® Game Engine, .NET/C#

July 2018, private project of Roland Bruggmann

## 2.2. External References

* <a href="https://youtu.be/KysSDO5oVDU" target="_blank">Screencast</a> on YouTube

---

# 3. Unity Rigged Body Animation

![Real-time Animation of Rigged Avatar by Motion Capture in Sensorimotor Lab.](TeaserRiggedBodyAnimation.jpg "Real-time Animation of Rigged Avatar by Motion Capture in Sensorimotor Lab.")
<p><em>Fig. 3.: Real-time Animation of Rigged Avatar by Motion Capture in Sensorimotor Lab.</em></p>

## 3.1. Short Summary

3D Content Generation and Interactive Real-time Animation of Rigged Avatar by Motion Capture in Sensorimotor Laboratory.

* **Index Terms:** Virtual Reality, 3D Modelling, Rigging, Motion Capture, Real-time Animation
* **Technology:** Blender, MakeHuman, Unity Game Engine, OptiTrack, Power-Wall

November &ndash; December 2018, Technology Platform for Research approved project "3D Workflow" aka "Rigged Body Animation in Unity" at Faculty of Human Sciences on behalf of Prof. Dr. Ernst-Joachim Hossner, Institute of Sport Science ISPW, Department of Movement and Exercise Science at University of Bern

## 3.2. External References

<!-- * <a href="https://youtu.be/FbmcLNf7JQM" target="_blank">Screencast</a> on YouTube -->
* <a href="https://www.tpf.philhum.unibe.ch/portfolio/RiggedBodyAnimation" target="_blank">*Rigged Body Animation in Unity®*</a>. In: Online-Portfolio of Technology Platform for Research TPF, Faculty of Human Sciences, University of Bern

---

# 4. UE4 Content for Dream-like VR

![Virtual Twin of the Dream Simulation Lab in Unreal Editor.](TeaserDreamSimLab.jpg "Virtual Twin of the Dream Simulation Lab in Unreal Editor.")
<p><em>Fig. 4.: Virtual Twin of the Dream Simulation Lab in Unreal Editor.</em></p>

## 4.1. Short Summary

*Modelling and Animation of 3D Objects for Use in a Dream-like Virtual Environment*

Experience of reality is highly flexible and unstable. This becomes apparent during the wake-sleep cycle when dreams appear real to us. To investigate alterations in the experience of reality and its underlying mechanism, a bizarre virtual environment is used to elicit altered experiences. Therefore, 3D objects and environments had to be created.

* **Index Terms:** Virtual Reality, 3D Modelling, Animation, Rotating Surface Photography, UV Mapping, Cloth Simulation, Fluid Simulation
* **Technology:** HTC VIVE Pro, Unreal Engine, UE C++-Plugin Development, Blender, GIMP, Nikon D80, Cannon EOS 60D, Nvidia Cloth, Nvidia Cataclysm

January &ndash; July 2019, Technology Platform for Research approved project "3D Content for Dream-like VR" at Faculty of Human Sciences on behalf of Prof. Dr. Fred Mast, Institute of Psychology, Department of Cognitive Psychology, Perception and Research Methods at University of Bern

## 4.2. Insights

Documentation: **<a href="https://www.slideshare.net/RolandBruggmann/3d-content-for-dreamlike-vr-249969767" target="_blank">Report (pdf)</a>** on SlideShare

Readme:

* UE Project: [Dream Simulation Lab](DreamSimLab)
* UE Code Plugin: [Bizarre BZR](BZR)
* UE Content Plugin: [Virtual Learning Attendance VIRLA](VIRLA)

## 4.3. External References

* <a href="https://www.tpf.philhum.unibe.ch/portfolio/dreamLikeVR" target="_blank">*3D Content for Dream-like VR*</a>. In: Online-Portfolio of Technology Platform for Research TPF, Faculty of Human Sciences, University of Bern
* <a href="https://www.rts.ch/play/tv/redirect/detail/12161998?startTime=358)" target="_blank">*Le pouvoir de l'imaginaire*</a>. In: *Faut pas croire*, émission du 01.05.2021 (video playback start time 5:58), Play RTS, Radio Télevision Suisse
* Denzer, Simone; Diezig, Sarah; Achermann, Peter; König, Thomas; Mast, Fred W. (2022). <a href="https://boris.unibe.ch/165396/" target="_blank">*BizarreVR: Dream-like bizarreness in immersive virtual reality induced changes in conscious experience of reality while leaving spatial presence intact*</a>. In: Consciousness and Cognition, 99, p. 103283. Elsevier <a href="http://dx.doi.org/10.1016/j.concog.2022.103283" target="_blank">10.1016/j.concog.2022.103283</a>

---

# 5. UE4 Display Cluster in CAVE

![UE Display Cluster Rendering of a 3D Scene in Sensorimotor Laboratory CAVE.](TeaserSensorimotorLab-3DRendering-CAVE.jpg "UE Display Cluster Rendering of a 3D Scene in Sensorimotor Laboratory CAVE.")
<p><em>Fig. 5.: UE Display Cluster, 3D Scene in Sensorimotor Laboratory CAVE.</em></p>

## 5.1. Short Summary

*Distributed Real-time Rendering in Sensorimotor Laboratory CAVE*

An Unreal Engine project based on the display cluster template "nDisplay" providing game-levels related to the Institute of Sports Science ISPW at University of Bern, more precisely for the sensorimotor lab of the institute with its five-sided CAVE. The lab integration is enabled by a newly developed messaging layer that is used to interact with an Event Broker. Custom-developed Unreal Engine plugins are used to control VR objects via the lab's experiment management system and render 360° videos and CAVE-specific 3D content. Due to the plugin-based architecture, the integration solution is modular and can also be used in other laboratories of the faculty.

* **Index Terms:** Virtual Reality, Cluster Rendering, Parallel Rendering, Real-time Rendering, CAVE, 3D, Steroscopy, 360° Video, Motion Capture, Eye Tracking, Integration
* **Technology:** Unreal Engine, UE Blueprint, UE C++-Plugin Development, UE nDisplay, Nvidia Mosaic, Nvidia Quadro with Sync, OptiTrack, PupilLabs, JSON/JSON-Schema, ZeroMQ

August 2019 - June 2021, Technology Platform for Research approved project "Distributed Game Engine DGE" at Faculty of Human Sciences on behalf of Prof. Dr. Ernst-Joachim Hossner, Institute of Sport Science ISPW, Department of Movement and Exercise Science at University of Bern

## 5.2. External References

* <a href="https://www.tpf.philhum.unibe.ch/portfolio/ue4DisplayCluster" target="_blank">*UE4 Display Cluster in CAVE*</a>. In: Online-Portfolio of Technology Platform for Research TPF, Faculty of Human Sciences, University of Bern
* <a href="https://www.ispw.unibe.ch/research/research_equipment/sensorimotor_lab/index_eng.html" target="_blank">*Research Equipment: Sensorimotor Lab*</a>. In: Website of the Institute of Sport Science, University of Bern
* Santina Russe: <a href="https://www.horizonte-magazin.ch/2021/09/02/einblick-in-den-blick-von-topathletinnen/" target="_blank">*Der Blick von Topathletinnen wird optimiert*</a>, 02. September 2021. In: Horizonte - Das Schweizer Forschungsmagazin, Fokus: Sport im Labor (Online), Hrsg: Schweizerischer Nationalfonds zur Förderung
der wissenschaftlichen Forschung (SNF)

<!-- * <a href="https://viscon.de/4-seiten-cave-fuer-universitaet-bern/" target="_blank">*4-Seiten-CAVE für Universität Bern*</a>, 15 December 2016. In: Website of Viscon GmbH -->
<!-- * [*Rendering to Multiple Displays with nDisplay*](https://docs.unrealengine.com/en-US/WorkingWithMedia/IntegratingMedia/nDisplay/index.html). In: Unreal Engine Documentation -->
<!-- * <a href="https://tube.switch.ch/videos/WgB89iKX2u" target="_blank">*Forschung am ISPW*</a>. In: ISPW-Imagefilme on SWITCH tube, Published by André Klostermann, Universität Bern on 15 March 2022. -->
<!-- * Gian Paul Lozza: <a href="https://www.horizonte-magazin.ch/2021/09/02/bildreportage-vermessene-bewegungen/" target="_blank">*Fotoreportage: Die Vermessung der kleinsten Bewegungen*</a>, 02. September 2021. In: Horizonte - Das Schweizer Forschungsmagazin, Fokus: Sport im Labor (Online), Hrsg: Schweizerischer Nationalfonds zur Förderung der wissenschaftlichen Forschung (SNF) -->

---

# 6. UE Plugin: Integration Tool

![UE Plugin: Integration Tool.](TeaserUEPluginIntegrationTool.jpg "UE Plugin: Integration Tool.")
<p><em>Fig. 6.: UE Plugin "Integration Tool", example PUB/SUB Scheme.</em></p>

## 6.1. Short Summary

*Adds Blueprint Support for Asynchronous Messaging using NNG&trade; next generation of nanomsg&trade; Software*

An Unreal Engine plugin enabling asynchronous, broker-less messaging using NNG&trade; next generation of nanomsg&trade; software from the Blueprint visual scripting system. The delivered assets provide transporting messages over a network and can be used in games to enable direct machine-to-machine communication, internet of things integration, or interaction with, e.g., an enterprise service bus or an event bus/broker resp. Other use cases could be data streaming or instant messaging from or into a game.

* **Index Terms:** Messaging, Integration, M2M, IoT, Network, TCP, INPROC, Socket, PubSub, Runtime
* **Technology:** Unreal Engine, UE Blueprint, UE C++-Plugin Development, NNG&trade;

April 2022, brug9 on Unreal Marketplace

## 6.2. External References

* <a href="https://github.com/brugr9/UEPluginIntegrationTool" target="_blank">*UE Plugin: Integration Tool &mdash; Documentation*</a> on github

---

# A. Unreal Online Learning: Achievements

I have the following knowledge:

* Proficient in working with UE Blueprints
* Expert know-how in providing with UE Content-Plugins and writing C++-Plugins&mdash;also by the use of 3rd party libraries
* Experience in Virtual Reality, Real-time Rendering, Motion Capture, Eye Tracking, Messaging and Integration in UE
* Solid understanding of general workflows and artistic works in UE
* Excellent organization skills with adherence to file structures and naming conventions

List of completed online learning courses: *<a href="https://forums.unrealengine.com/u/brugr9/badges" target="_blank">Badges on forums.unrealengine.com</a>*
<!-- [List of completed on-line learning courses](UE-Achievements) -->

---

[<< Back to *https://about.me/rbruggmann*](https://about.me/rbruggmann)
