---
layout: post
title:  "DIY Hardware 2FA Token: Pi Zero + Waveshare E-Ink + PiSugar Button + QR Scanner + AI"
date:   2025-12-05 23:08:30 +1100
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

The project started as a series of ChatGPT iterations. The aim was to explore GPT possiblities as an aide in rapid prototyping and it worked flawlessly. The main approach was not focused on me troubleshootng the code but rather giving GPT clues to help and fix it's code as we did move.




<!-- Ideas - principles - targets (no deep-dive, set tasks,  show the issue to AI for troublshooting) -->

<!-- Things that worked out of the box -->


# Buldout and tests



## Software

Building this project as a python pachage was another part of exploration journey as I was curious to make and installable and maintainable package that would have all the features of a grown-up software:

 - repository
 - installation and update logic
 - Systemd integrations
 - etc
 

## Hardware


### SOC - Raspberry Pi Zero 2W

Pizero 2W is a great platform for tinkering. It is quite powerful to host almost anything.

### Case and 3D Printing

I also was keen to explore what current resources available for 3D printing in 2025. Since I stuck with the pwnagotchi project as base for our FOB [this case](https://www.thingiverse.com/thing:6446341) was chosen as donor for the project. I was quite impressed by what [Craftcloud](https://craftcloud3d.com/) can offer, especially when you have your STL file at hand. I was able to log my orders within 10 minuts, and they were printed almost straight away. (no affilation here, just impressed user).



#Nuances that we need to fix

<!-- Display refresh -->
<!-- power consumption -->
<!-- cases -->
<!-- dangling camera-->

#Project code

Project code can be foound [in this repository](https://github.com/nikkuz/otp_zerow_project).


# Future improvements


## case and stl

<!-- Printcloud -->

## Partial screen refresh


## Vibecode environment

Explore writing code with cursor and keeping custom set of instructions to improve interactions with AI in regards to output file requirements, documentation and more.