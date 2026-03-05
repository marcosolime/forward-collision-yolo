# Forward Collision Warning – ADAS Demo

<p align="center">
    <img src="cover.jpeg" width="40%">
</p>

## Overview

This repository contains a **minimal prototype of an ADAS perception module** that simulates a **Forward Collision Warning (FCW)** system.

The demo processes a dashcam video, detects road participants, estimates their distance from the ego vehicle, and triggers a warning when an object is too close.

The implementation is provided in a single notebook:

```
demo.ipynb
```

## Features

* Object detection (vehicles, pedestrians, bicycles)
* Monocular distance estimation
* Collision warning logic
* Video visualization with bounding boxes and alerts

## Tech Stack

* Python
* YOLOv8
* OpenCV
* NumPy

## Running the Demo

1. Install dependencies

```
pip install -r requirements.txt
```

2. Open and run the notebook

```
demo.ipynb
```

## Notes

This is a **simplified research/demo prototype** intended to illustrate the core ideas behind perception systems used in **Advanced Driver Assistance Systems (ADAS)**.
