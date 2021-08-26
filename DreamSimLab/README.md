# Unreal Engine Project: Dream Simulation Lab

Version: v2.1.0
<br>Author: Roland Bruggmann

## Description

![Screenshot of Project Content](Docs/ScreenshotProjectContent.jpg "Screenshot of Project Content")

A project based on UE template 'Virtual Reality' providing with Institute of Psychology related maps, more precise for the Dream Simulation Laboratory with its Room D268. This project was elaborated as TPF approved project '3D Content for Dream-Like VR - Modelling and Animation of Bizarre 3D Objects for Use in a Dream-Like Virtual Environment' (aka BZR).

### Features

* Maps: DreamSimLab which is a digital twin of Institue of Psychology's Virtual Reality Lab Room D268 supplemented with actors from plugin BZR.

### Contents

* Maps: 1
* Map Build Data Registry: 1

### Important Notes

* Platforms Tested: PC Windows
* Supported Engine Versions: 4.26

---

## Table of Contents

<!-- Start Document Outline -->

* [1. Usage](#1-usage)
  * [1.1. Dependencies](#11-dependencies)
  * [1.2. Installation](#12-installation)
* [2. Map DreamSimLab](#2-dreamsimlab)
* [A. References](#a-references)

<!-- End Document Outline -->

<div style='page-break-after: always'></div>

## 1. Usage

### 1.1. Dependencies

The project was developed using

* Windows 10
* Visual Studio 2019
* Unreal Engine 4.26
* UE Project Template 'Virtual Reality'

The project makes use of plugin [BZR](../BZR) and [VIRLA](../VIRLA).

### 1.2. Installation

Download the project using git -- the plugins are included as git submodules:

```shell
git clone --recursive https://github.com/brugr9/DreamSimLab.git
cd DreamSimLab
git submodule update --recursive
```

<div style='page-break-after: always'></div>

## 2. Map DreamSimLab

The map `DreamSimLab` is a copy from plugin VIRLA's map `RaumBern` supplemented with actors from plugin BZR:

* ArtPrint (Bizarre)
* Book (Bizarre)
* Jacket (Bizarre)
* MarkerPen (Bizarre)
* Telephone (Bizarre)
* Corridor and Room Lamps

Screenshot of Map DreamSimLab:

![Screenshot of Map DreamSimLab](Docs/Screenshot-Map-DreamSimLab.jpg "Screenshot of Map DreamSimLab")

Screenshot of WorldSettings Lightmass:

![Screenshot of WorldSettings Lightmass](Docs/UE4-WorldSettings-Lightmass.jpg "Screenshot of WorldSettings Lightmass")

## A. References

* [*3D Content for Dream-Like VR*](https://www.tpf.philhum.unibe.ch/portfolio/dreamLikeVR), In: Online-Portfolio of Technology Platform for Research TPF, Faculty of Human Sciences, University of Bern
* [*Virtual-Reality-Lab*](https://www.kog.psy.unibe.ch/research/labors/virtual_reality_lab/index_eng.html), In: Webpages of Institute of Psychology, Division of Cognitive Psychology, Perception and Research Methods, University of Bern
* [*“Le pouvoir de l'imaginaire”*](https://www.rts.ch/play/embed?urn=urn:rts:video:12161998&startTime=358&subdivisions=false) (Start Time 05:58), RTS Radio Télevision Suisse, 01.05.2021
