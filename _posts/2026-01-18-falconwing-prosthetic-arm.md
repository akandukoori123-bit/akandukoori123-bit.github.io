---
title: "Falconwing: a 3D-printed, muscle-controlled prosthetic arm"
date: 2026-01-18 09:00:00 -0400
categories: [Projects, Engineering]
tags: [arduino, emg, 3d-printing, robotics]
---

**Falconwing** is a 3D-printed, Arduino-based prosthetic arm my team and I built
that grips on command using your own muscle signals.

The control system uses **MyoWare EMG sensors** to read electrical activity from a
muscle. When the sensor detects you flexing, the Arduino drives the grasping
mechanism to close; relax, and it opens. The hand and frame are 3D-printed, which
kept it cheap to iterate on and easy to reprint when a part needed to change.

The hard part wasn't any single piece — it was getting sensing, electronics,
mechanics, and code to cooperate reliably. Noisy EMG readings, thresholds that
drift, and mechanical play all had to be tuned together. Doing it as a team meant
splitting the problem and trusting each other's parts to hold up.
