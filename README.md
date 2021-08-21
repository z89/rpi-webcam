<a href="https://github.com/z89/nextjs-tor-v3"><div  align="center"><img src="https://i.imgur.com/iiHnpiH.png" alt="Logo"></div></a>

<div align="center">
<img src="https://img.shields.io/badge/python-v2.7-blue?style=for-the-badge&logo=python"></img>
<img src="https://img.shields.io/badge/apache-v2.4.38-blue?style=for-the-badge&logo=apache"></img>
<img src="https://img.shields.io/badge/php-v7.3.29-red?style=for-the-badge&logo=php"></img>
<br>
<img src="https://img.shields.io/badge/raspberry pi os-supported-green?style=for-the-badge&logo=tor"></img>
<img src="https://img.shields.io/badge/debian-supported-green?style=for-the-badge&logo=tor"></img>
</div>
<br>
<p align="center">a guide to setup a <strong>raspberry pi pan-tilt camera </strong> with a <strong>vanilla JS web interface</strong> using <strong>python, php & apache!</strong>

<br>
<br>
<strong><p  align="center">z89 (author): this is not a comprehensive or official guide to setup up a RPi pan-tilt camera with a web interface, this is soley for my personal reference. Please refer to the official docs from the forked repos used in this custom project for an official tutorial. As always, use anything in this repo at your own risk as you can potentially damage your servo motors!</p></strong>
<br>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [About](#about-the-guide)
- [Installing](#backend-installation)
  - [1. Hardware (RPi Servo Motors & Camera)](#hardware-installation)
  - [2. Software (Web Interface & Python Scripts)](#software-installation)

<!-- ABOUT THE PROJECT -->
<br>

## About The Guide

_Last Updated 21/08/2021_:

As stated above, this is a custom guide made for my own personal reference. Click [here](https://github.com/sparkfun/RPi_PanTilt_Camera_Kit/) to view the official pan-tilt repo, and click [here](https://github.com/silvanmelchior/RPi_Cam_Web_Interface) to view the official web interface repo. This repo contains submodule repos which are forks from the official repos, and these forks only contain minor changes. Feel free to explore these changes if you decide to use this repo.

<!-- HARDWARE INSTALLATION -->
<br>

## Hardware Installation

To get started with this project, you must assemble the hardware by connecting your pi to your camera and servo motors. A guide from the pan-tilt repo can be found [here](https://learn.sparkfun.com/tutorials/setting-up-the-pi-zero-wireless-pan-tilt-camera?), but you may be using a different [HAT](https://github.com/raspberrypi/hats) for your RPi, so make sure to follow your manufacturers documentation. After completing the guide, your project should look similar to the picture found [here](https://cdn.sparkfun.com/r/600-600/assets/learn_tutorials/6/5/8/Pi_Servo_Cam_Guide-36.jpg).

<!-- HARDWARE INSTALLATION -->
<br>

## Software Installation
