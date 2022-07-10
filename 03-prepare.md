---
title: "Preparing an SD Card"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- Where do you download the Raspberry Pi imager from?
- How do you install the Raspberry Pi imager on your computer?
- 

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- download and install the Raspberry Pi imager
- download and install the CarpentriesOffline image
- write the CarpentriesOffline image to the SD Card
- connect to the Raspberry Pi Access Point

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

Every computer needs to load an operating system when you switch it on. Therefore it will usually have a default place where it will look for an operating system in the first place. The process of loading the operating system is called **booting**. In general, if someone tells you to reboot your computer it means to switch is off and switch it back on again so that the operating system can be loaded from scratch. In the case of your desktop or laptop computers you will have a hard drive built into the computer or alternatively you might be able to boot from a USB device.

In the case of the Raspberry Pi its default booting device is an SD card. Pre-RPi3 used a mini-SD card but RPi3 and RPi4 use micro-SD cards. SD cards are available in various capacities, ie. the amount of information that can be stored on it. A basic operating system for the Pi will probably take about 2GB but then you will also need space for all the Carpentries lesson files and other software that you want to make available to the learners. 

Usually when you buy a RPi you can also buy an SD card with the operating system pre-loaded. Alternatively you can buy an empty SD card and prepare it yourself. Preparing the SD card involves downloading an **image** of the operating system (and there are various versions available), downloading the software, Raspberry Pi Imager, required for writing the image to the SD card and then using the software to write the image to the SD card.

The CarpentriesOffline team is building an **image** that can be written to the SD card that contains the operating system and all the required files. This image is about 5GB at the moment. So you will need an SD card that can hold at least that. 



::: challenge 

## Challenge 1: What software do you need to prepare an SD card?

1. Word
2. Excel
3. Raspberry Pi Imager
4. Ubuntu
5. Raspbian

:::::: solution

1. Word cannot be used to prepare an SD card, it is a word processor.
3. Excel cannot be used to prepare an SD card, it is a spreadsheet.
4. The correct answer is *3*

::::::

:::

::: challenge

## Challenge 2: Where would you find the CarpentriesOffline image?

1. On the Raspberry Pi website
2. On The Carpentries website
3. On the CarpentriesOffline website
4. On the Microsoft website?

:::::: solution

::::::

:::

::::::::::::::::::::::::::::::::::::: keypoints 

- Know where to download the Raspberry Pi Imager from
- Know how to install the Raspberry Pi Imager
- Know where to download the CarpentriesOffline RPi image
- Know how to write the CarpentriesOffline image to an SD card
- Know how to start up the RPi as an Access Point and Server for learners to connect to.

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
