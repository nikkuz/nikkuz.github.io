---
layout: post
title:  "OTP FOB tinkering"
date:   2023-03-01 23:08:30 +1100
categories: jekyll update
---

# Preface

## Disclamer


This project is purely instrumental and doesn't have any practical value apart from me exploring several technologies and ideas.


## Technologies and ideas explored


- Raspberry Pi Zero 2W: I've always had an itch to build sometihng on this platform
- TOTP and overall magic around 2FA
- QR codes
- Vibcoding
- 3D printing in 2025
- github pages for documenting stuff

This all comes down as a FOB device that I'm currently working on.

# TOTP and motivation


Exciting magic about TOTP is that once set up, it does not need any particular network connection as the module relies completely on time and a shared secret that was calculated during the initial setup.

OTP keys are regenerated every 30 seconds, which makes an ideal candidate data to be displayed on a e-ink display.

Since the FOB itself will not need any connectivity and will consume minimum power to run a display and Raspbian itself, paring the device with a small battery would make the FOB useful and live beyond the lab power source.


<!-- no network and syncronus -->

# QR codes

<!-- Magic -->


# Vibecoding

<!-- Ideas - principles - targets (no deep-dive, set tasks,  show the issue to AI for troublshooting) -->

<!-- Things that worked out of the box -->


# Buldout and tests

## Software

## Hardware

<!-- pwnagotchi project as a donor works suprisingly well + pisugar -->

## 3D Printing

I purchased initial hardware for pwnagotchi and figured there's plenty of cases out there available for print. Adding camera to that project was a bit ad-hoc and, as with every project requirement coming late - it didn't fit (unsurprisingly). So my initial prototype has a camera sticked to the side of the case with a camera cable dangling at the side. 

I managed to print the case using a Printcloud service and was extremely satisfied with the results, taking into account that the whole printing task (select model, find sercice, upload model and choosing materials, etc) was done in background from my phone, while I was busy with something else.



<!-- Printcloud -->

##Case and STL

Taking the whole printing experience into account I was under impression that maybe I could give it a try to adjust the initial model with AI and print updated case. However, GPT can't render at this point so we had to go down the path of installing openscad and editing script that would adjust the original model. That wasn't successful yet, so - dangling camera goes to the backlog of fixes.


<!-- Printcloud -->


#Nuances that we need to fix

<!-- Display refresh -->
<!-- power consumption -->
<!-- cases -->
<!-- dangling camera-->

#Project code



