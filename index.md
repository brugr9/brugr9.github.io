# Unreal Engine Projects and Plugins

## Sensorimotor Lab

**Distributed Real-Time Rendering in Sensorimotor Laboratory**

![Screenshot of an Ice Hockey Scene as 360° Spherical Video Playback in Unreal Editor.](TeaserSensorimotorLab-360DegVideo-UnrealEditor.jpg "Screenshot of an Ice Hockey Scene as 360° Spherical Video Playback in Unreal Editor.")
<p><em>Fig.1: Screenshot of an Ice Hockey Scene as 360° Spherical Video Playback in Unreal Editor.</em></p>

![The same Ice Hockey Scene as Unreal Engine 360° Spherical Video Playback in Sensorimotor Laboratory CAVE.](TeaserSensorimotorLab-360DegVideo-CAVE.jpg "The same Ice Hockey Scene as Unreal Engine 360° Spherical Video Playback in Sensorimotor Laboratory CAVE.")
<p><em>Fig.2: The same Ice Hockey Scene as Unreal Engine 360° Spherical Video Playback in Sensorimotor Laboratory CAVE.</em></p>

An Unreal Engine project based on the display cluster template "nDisplay" providing game-levels related to the Institute of Sports Science ISPW at University of Bern, more precisely for the sensorimotor lab of the institute with its five-sided CAVE. The lab integration is enabled by a newly developed messaging layer that is used to interact with an Enterprise Service Bus ESB. Custom-developed Unreal Engine plugins are used to control VR objects via the lab's experiment management system and render 360° videos and CAVE-specific 3D content. Due to the plugin-based architecture, the integration solution is modular and can also be used in other laboratories of the faculty.

* [UE Display Cluster Project "Sensorimotor Lab"](SensorimotorLab)
  * [Blueprint Plugin "Play Area"](PlayArea)
  * [Blueprint Plugin "Immersive Video"](ImmersiveVideo)
  * [Blueprint Plugin "Sports Equipment"](SportsEquipment)
  * [Blueprint Plugin "AprilTag Images"](AprilTagImages)
  * [Code Plugin "Pupil Core"](Pupil)
  * [Code Plugin "ZeroMQ"](ZeroMQ)
  * [Code Plugin "ESB Messaging"](ESBMessaging)
  * [Code Plugin "Distributed Game Engine DGE"](DGE)
  * [Blueprint Plugin "Institute of Sport Science ISPW"](ISPW)
* [Integration Testing by Jupyter Notebook as ESB Messaging Endpoint](ISPW/Testing/)

August 2019 - June 2021, Technology Platform for Research TPF approved project "Distributed Game Engine DGE" aka "UE4 Display Cluster in CAVE" and subsequent projects at Faculty of Human Sciences on behalf of the Institute of Sport Science ISPW, Department of Movement and Exercise Science at University of Bern. Only the documentation is publicly available (cp. [UE4 Display Cluster in CAVE](https://www.tpf.philhum.unibe.ch/portfolio/ue4DisplayCluster), In: Online-Portfolio of Technology Platform for Research).

## Dream Simulation Lab

**Modelling and Animation of 3D Objects for Use in a Dream-Like Virtual Environment**

![Virtual Twin of the Dream Simulation Lab in Unreal Editor.](TeaserDreamSimLab.jpg "Virtual Twin of the Dream Simulation Lab in Unreal Editor.")
<p><em>Fig.3: Virtual Twin of the Dream Simulation Lab in Unreal Editor.</em></p>

Experience of reality is highly flexible and unstable. This becomes apparent during the wake-sleep cycle when dreams appear real to us. To investigate alterations in the experience of reality and its underlying mechanism, a bizarre virtual environment is used to elicit altered experiences. Therefore, 3D objects and environments had to be created.

* [UE Virtual Reality Project "Dream Simulation Lab"](DreamSimLab)
  <!-- * [Content Plugin "Virtual Learning Attendance VIRLA"](VIRLA) -->
  * [Code Plugin "Bizarre BZR"](BZR)

January-July 2019, Technology Platform for Research approved project "3D Content for Dream-Like VR" at Faculty of Human Sciences on behalf of the Institute of Psychology, Department of Cognitive Psychology, Perception and Research Methods at University of Bern. Only the documentation is publicly available (cp. [3D Content for Dream-Like VR](https://www.tpf.philhum.unibe.ch/portfolio/dreamLikeVR), In: Online-Portfolio of Technology Platform for Research).

# Unity® Projects and Plugins

## Volume Rendering

**Plug-in for Rendering of Medical Data**

![Real-Time Rendering of a Neurovascular Angiography in Unity Editor.](TeaserVolumeRendering.jpg "Real-Time Rendering of a Neurovascular Angiography in Unity Editor.")
<p><em>Fig.4: Real-Time Rendering of a Neurovascular Angiography in the Unity® Editor.</em></p>

In the context of my Bachelor's Thesis I implemented a Unity® plug-in for 3D visualisation of MRI/CT data which can be used in VR/AR applications. Therefore I wrote a raycaster pixel-shader running on GPUs.

* ["Unity® Volume Rendering—Plug-in for Rendering of Medical Data"](https://www.linkedin.com/pulse/unity-volume-rendering-roland-bruggmann/), In: LinkedIn.

January-June 2016, Institute for Human Centered Engineering HuCE, Laboratory for Computer Perception and Virtual Reality, Bern University of Applied Sciences BUAS. Only the documentation is publicly available.
