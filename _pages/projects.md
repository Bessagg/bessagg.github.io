---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

# Table of Contents
- [Surgical Instruments Detection with Yolo](#surgical-detection)
- [Patient's Clinical Outcome Prediction](#patient-outcome-prediction)
- [Model aggregation to forecast reservoir production](#forecast-oil-production)
- [Car suspension design](#apuama)

---
## Surgical Instruments Detection with Yolo (2024 --)
 -	The objective was to automate inventory managment with computer vision. A task that took over 30minutes, was done in less than 10 seconds using our AI app and phone camera.
 -	The model identified missing components. YoLo model was used with custom training.
 -	Some components (screws) were identified by their positions in the box, different clustering algorithms were used to split components in regions, rows and columns, so the exact missing component's name was identified.
 -	The components and the containers were made of aluminium, which is reflective and yields low contrast. So I tested different light conditions, camera position and opencv morphological transformations. Some of the crazy tests and the solution's evolution are displayed below.


<table>
  <tr>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_0.jpeg?raw=true" 
           alt="detection_0" height="300"/>
      <div><b>(a)</b> - Some strange results when I was playing with distortion correction, trying to fix the box's deformation, being suken in the center, which made it harder to group screws in columns/rows.</div> <!-- Placeholder for description -->
    </td>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_1.jpeg?raw=true" 
           alt="detection_1" height="300"/>
      <div><b>(b)</b> - Initial setup to control light conditions and detections with opencv.</div> <!-- Placeholder for description -->
    </td>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_01.jpeg?raw=true" 
           alt="detection_01" height="300"/>
      <div><b>(c)</b> - Transformations in opencv to deal with the lack of contrast</div> <!-- Placeholder for description -->
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_3.jpeg?raw=true" 
           alt="detection_3" height="300"/>
      <div><b>(d)</b> - Great results with a light panel.</div> <!-- Placeholder for description -->
    </td>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_4.jpeg?raw=true" 
           alt="detection_4" height="300"/>
      <div><b>(e)</b> - Achieved great results in natural light conditions.</div> <!-- Placeholder for description -->
    </td>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_5.jpeg?raw=true" 
           alt="detection_5" height="300"/>
      <div><b>(f)</b> - Detections with a segmentation model.</div> <!-- Placeholder for description -->
    </td>
  </tr>
  <tr>
    <td colspan="3" align="center">
      <video height="300" controls>
        <source src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_video.mp4?raw=true" 
                type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div><b>(g)</b> - App with solution</div>
    </td>
  </tr>
</table>
---
## Patient's Clinical Outcome Prediction (2023 --)
- Objective: Accelerate treatment for high-risk patients by leveraging real-time data.
- Developed, evaluated and monitored models for patient's clinical outcome prediction. Deployed APIs for integration with the app.
- EHR (Electronic Health Record) data is continuously updated before the patient’s next scheduled consultation, potentially indicating risks in real-time. The model operates 24/7, delivering instant alerts to physicians and performing risk stratification, enabling faster interventions and improving patient outcomes.


<p align="center">
  <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/invisual_dash.jpeg?raw=true" alt="tiredata" width="800"/>
</p>



---
## Model aggregation to forecast medium-term reservoir production (2020 - 2021)
 -	Scientific initiation project, with a published paper in on of the biggest energy congress of the world, Rio Oil and Gas.
 -	I worked at Fortaleza's research group, STORMS. We used realizations of a benchmark resevouir model "OLYMPUS" as models to forecast production.
 -	We associated weights to each model and tested different optimization alogirthms to minimize a developed loss function.
 -	This strategy was validated with an average prediction error below 5%;


<p align="center">
  <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/model_agreg2.png?raw=true" alt="tiredata" width="800"/>
</p>


## Car suspension design - Apuama Racing - FSAE (2018 - 2019)
-	Used mathematical models to create vehicle simulations (point-mass-model, biclycle-model).
-	Developed a Suspension distribution forces program in Matlab. We would use the maximum forces obtained in braking and cornering simulations to dimension and reduce mass of the suspension.
-	Project to reduce steering torque for better handling of the vehicle.
-	Method to measure the car's center of gravity and validate simulations.

<table>
  <tr>
    <td>
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/hosier_tire_data.jpg?raw=true" alt="tiredata" height="400"/>
    </td>
    <td>
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/suspa_1.jpeg?raw=true" alt="suspa" height="400"/>
    </td>
  </tr>
</table>


--- 
