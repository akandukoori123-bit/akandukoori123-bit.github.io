---
title: "AUMP: ML early warning for crashing bradycardia"
date: 2026-06-10 09:00:00 -0400
categories: [Projects, Machine Learning]
tags: [ml, healthcare, gemma, kaggle]
pin: true
---

**AUMP** is a machine learning system I built solo for the Kaggle Gemma 4
Hackathon. It predicts bradycardic cardiac events earlier than standard threshold
monitors: a median 3-step lead time at 100% sensitivity and 70.7% specificity
across 200 evaluation scenarios.

I engineered temporal features from heart-rate time series, benchmarked logistic
regression and random forest models, and integrated Gemma 4 function calling to
build an agentic clinical alert layer with severity assessment, contraindication
detection, and multilingual output. Code is on
[GitHub](https://github.com/akandukoori123-bit/AUMP).
