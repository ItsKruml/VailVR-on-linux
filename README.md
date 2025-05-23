# VailVR-on-linux
A Written tutorial for installing, optimizing and troubleshooting VailVR on most VR HMD´s with Linux support.
This has yet to be updated, so it might not work and is not fully complete as of 2025/20/5
###########################################################################################################

## Table of contents
- [Overview](#overview)
- [Drawbacks of Steamvr on linux](#Drawbacks)
- [Requirements](#Requirements)
  - [Pc Hardware](#pchwrd)
  - [Supported distros](#Supporteddistros)
  - [Supported and tested headsets under linux](#SupportedHMDs)
- [Reccomended Distro installation](#distroinstall)
  - [Additional software installation](#steaminstall)
  - [Proton-GE installation on reccomended distro](#protoninstall)
  - [Proton Activation](#ProtonON)
- [Credits](#credits)
- [Potenial Additions](#whatfuture)

## Overview

These are my own written down instructions and reccomendations to running vail and other Vr titles on Linux
As im in now way employed by AEXLAB to do this or have any incentive to provide proper support on this topic, this is just meant as a guide and is not a set in stone best way to run this game.
Also this will most likely not be updated unless i encounter issues on my personal machine running Linux VR or someone i know Annoyes me enough that i take action.
**HOWEVER** If you are running in to problems feel free to ask me **_IN THE DEDICATED CHANNEL_** For "Vail linux progress" in the [Official Vail Discord server](https://discord.gg/vailvr).
**_DONT EVEN DARE TO DM ME ABOUT THIS UNLESS I KNOW YOU FROM THERE_**

## Drawbacks of Steamvr on linux

Linux VR has many different implementations With steamvr being the most known but also the least reliable when it comes to actually running Anything.
Other Examples like [WiVRn](https://github.com/WiVRn/WiVRn) which have been proven to be better at running OpenVR/OpenXR titles than Steamvr.
Yet I will still be (As of now) only be showing how to play on Steamvr as it is the easiest (in my eyes) to set up with the hardware I use (Valve Index).
More drawbacks of steamvr is not being able to use Asynchronous Reprojection more commonly known as "Asynchronous Space warp" ore use any Reprojection reliably.
The issue with not having reprojection are the following:
* (possible) Jittery tracking for non lighthouse based tracking methods
* Less smoothness when not achievingenough frames to match the set refresh rate
* Higher input lag when not achievingenough frames to match the set refresh rate.

These issues do not present themselves when acheeving enough frames for the set refresh rate so lowering it might help for lower powered hardware. (rtx3060/rx6600 or worse when running an oculus quest 2)
<sub> (more might be added here..) </sub>

## Requirements
To run Steamvr and VailVR on Linux I will mention below what hardware you will need for a "Minimum" setup and a "Recommended" setup.

The Minimum requirement will be able to run VailVR and Steamvr on Linux though be it with ether bad performance (less than set refresh rate) or with low reliability (Hassle to set up Everytime for regular use).

The recommended hardware will be able to run the game on at least native resolution and run that at a frame rate matching the refresh rate of the headset (in my case a Q2 or Index so ether 120 or 144hz).

# Recommended PC hardware
For a CPU id recommend anything Ryzen 3 1st gen or  **or better** gen for a Minimum build and a <sub> something Intel </sub>

to be continued...



