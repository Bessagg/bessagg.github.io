---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---
# Table of Contents
- [Fracture Characterisation and Geometry for Motion Planning](#fracture-characterisation-and-geometry-for-motion-planning)
- [Fracture Detection and Localisation](#fracture-detection-and-localisation)
- [Bilateral Teleoperation Franka Panda and Geomagic](#bilateral-teleoperation-franka-panda-and-geomagic)
- [Hololyo](#hololyo)
- [Nao Interface](#nao-interface)
- [The Little Knight](#the-little-knight)


### Patient's Clinical Outcome Prediction
Description


include content

### Surgical Instruments Detection with Yolo
The objective was to automate inventory managment with computer vision. A task that took over 30minutes, was done in less than 10 seconds using our AI app.
The model would check a surgery utils box and output the identified missing components.
Some components (screws) were identified by their positions in the box, different clustering algorithms were used to split components in regions, rows and columns, so the exact component's ID was identified.

Some empirical/artsy tests were done at the beggining to enhance detection with light conditions, camera position and opencv morphological transformations. Because, the components and the containers were made of aluminium, which is reflective and yields low contrast.
The solution was included in an app where an operator can take a photo with his cellphone, upload the image and confirm/correct the used components after surgery.

- Yolo
- Segmentation Models
- Clustering algorithms
- FastAPI


### Model aggregation to forecast medium-term reservoir production [2022]
This was my scientific initiation project with a paper publishing in on of the biggest energy congress of the world.
I worked in Fortaleza's research group, STORMS. We used realizations of a benchmark resevouir model "OLYMPUS" as models to forecast production.
We associated weights to each model and formulated a loss function and tested different optimization algorithms.
This strategy was validated with an average prediction error below 5%;


--- 
