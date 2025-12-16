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

## software

## hardware

<!-- pwnagotchi project as a donor works suprisingly well + pisugar -->

## 3D Printing

<!-- Printcloud -->

## case and stl

<!-- Printcloud -->


# Nuances that we need to fix

<!-- Display refresh -->
<!-- power consumption -->
<!-- cases -->


# Project code



