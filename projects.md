---
layout: page
title: Volatile Vectors - Projects
description: Virtual Reality Prototypes, Projects, and Assets
sitemap:
    priority: 0.7
    lastmod: 2019-09-11
    changefreq: weekly
---
## SLiquid

SLiquid is a simple and lighweight VR-ready fluid simulation suitable for Unity's legacy, LWRP & URP render pipelines. Inspired by [Job/Vaction Simulator's liquids](https://uploadvr.com/job-simulator-coffee) the focus is on performance instead of physical acuracy, making it a viable choice not only for desktop but also mobile hardware like the Oculus Quest.

{% include youtube.html id="qtwuqpOueMI" %}

Get it [here](https://github.com/VolatileVectors/SLiquid).

## SnapXR

SnapXR is a VR-enabled GIF replay recorder for Unity. It automatically records the past few seconds of gameplay to a GIF file on demand. Frames are grabbed using Unity's AsyncGPUReadback.Request API to grab frames without stalling. GIF Encoding is done in a lowpriority backgroundthread in order to not interfer with the main gameplay loop. SnapXR is provided as an easy to configure component that can be attached to any camera (normal and stereoscopic alike) to record GIFs from whatever a camera renders in Unity.

<div class="box alt">
    <div class="row 50% uniform">
        <div class="6u"><span class="image fit"><img src="{{ "/images/sample.gif" | absolute_url }}" alt="" /></span></div>
        <div class="6u$"><span class="image fit"><img src="{{ "/images/inspector.jpg" | absolute_url }}" alt="" /></span></div>
    </div>
</div>

Get it [here](https://github.com/VolatileVectors/SnapXR).

## Diegetic Interface Sample

A small self contained sample showing how to build diegetic interfaces using [Tilia's](https://github.com/ExtendRealityLtd?q=tilia) controllables prefabs:

{% include youtube.html id="Uspp3LwRN2k" %}

Get it [here](https://github.com/VolatileVectors/Tilia-Controllables).

## Neon Jungle

A procedurally generated rouge-lite, with configurable smooth locomotion and gaze-based interactions:

{% include youtube.html id="Gb5isKzjzfY" %}

In collaboration with [Dustin Lacewell](https://github.com/dustinlacewell).

## Unstable Universes

Motivated by this [Solar System](https://www.youtube.com/watch?v=7axImc1sxa0) and the arrival of Unity's new Job system Unstable Universes was born.
Due to the magic of the Job system, Unity Mathematics, and the Burst Compiler the trajectory simulation can handle a few hundred thousand timesteps per frame updating in real time, instead of taking over a second for a few thousand steps:

{% include youtube.html id="5SRGLvR3qH8" %}

Afterwards you can take a trip through it:

{% include youtube.html id="yvjiz8kkVOc" %}

The project and code can be found [here](https://github.com/VolatileVectors/Unstable-Universes).
(The non-free art assets used had to be stripped from the github repository though)

## Entanglement

This started as a [VR Jam 2020](https://itch.io/jam/vr-jam-2020) idea with the theme "One tool many jobs". A shooter engineered around a quantum entanglement revolver using different types of ammunition to manipulate objects and bend time and space.

{% include youtube.html id="M8EpycnaDbM" %}

The project and code can be found [here](https://github.com/VolatileVectors/Entanglement).
(The non-free art assets used had to be stripped from the github repository though)