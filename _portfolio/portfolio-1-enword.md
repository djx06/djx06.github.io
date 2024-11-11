---
title: "EnWord: Unknown Word Detection for English as a Second Language (ESL) Learners Using Gaze and Pre-trained Language Models"
excerpt: "This paper presents a transformer-based machine learning model that aligns gaze trajectory with corresponding text and decodes the probability of unknown words within the text in real time with high precision. <br/><img src='/images/enword/demo_clip.gif'>"
collection: portfolio
---

Face orientation can often indicate users’ intended interaction target. In this paper, we propose \name, a novel face tracking technique based on acoustic ranging using earphones. FaceOri can leverage the speaker on a commodity device to emit an ultrasonic chirp, which is picked up by the set of microphones on the user's earphone, and then processed to calculate the distance from each microphone to the device. These measurements are used to derive the user’s face orientation and distance with respect to the device. We conduct a ground truth comparison and user study to evaluate FaceOri's performance. The results show that the system can determine whether the user orients to the device at a 93.5% accuracy within a 1.5 meters range. Furthermore, FaceOri can continuously track user's head orientation with a median absolute error of 10.9 mm in the distance, 3.7$^\circ$ in yaw, and 5.8$^\circ$ in pitch. FaceOri can allow for convenient hands-free control of devices and produce more intelligent context-aware interactions.

# Motivation
* The earphone has become  one of the most ubiquitous computing devices with the ability of ultrasonic ranging.
* Users tend to orient their heads toward their intended interaction target.
* Enabling a device to detect this intention precisely and naturally can simplify user interface flow, enable hands-free interaction, and adapt interfaces to the context of use.

# Contributions
* A spatial input technique that applies ultrasonic ranging to enable continuous head orientation and distance tracking with respect to a device with a speaker using a built-in set of microphones in the commodity ANC earphone.
* An end-to-end system characterization and user evaluation demonstrate FaceOri's high dynamic performance in continuous tracking and binarized attention detection.
* An exploration of the application space afforded by FaceOri with prototypes of selected demonstrative experiences, showcasing the applicability of the proposed approach.

# Method
### Software
FaceOri can enable continuous head position and orientation tracking (A) with FMCW-based acoustic ranging or binarized attention classification without calibration (B).
<img src='/images/faceori/software.png'>

### Hardware
FaceOri’s earphone hardware has a commodity earphone hardware (MPOW H19 for demonstration), an MPU-9250 IMU, an audio interface, and a laptop to process the audio signal.
<img src='/images/faceori/hardware_imp.jpg'>

# Results
### Tracking Accuracy (median absolute error)
FaceOri can continuously track the user’s head orientation with a median absolute error of 10.9 mm in the distance, 3.7◦ in yaw, and 5.8◦ in pitch. 

|          | FaceOri | CAT (SOTA) |
|----------|---------|------------|
| Yaw      | 3.7°    | 11.0°      |
| Pitch    | 5.8°    | 11.6°      |
| Distance | 10.9 mm | 42.0 mm    |

### Binary Classification Accuracy: 93.5%

### Dropped Frames
FaceOri is more robust against the non-LOS and Doppler effect introduced by the head motion.
<img src='/images/faceori/drop_frame.png'>

# My Contributions
* Modified the algorithm to improve the  performance in low signal-to-noise ratio scenario.
* Designed and conducted the user study.
* Enabled the binarized attention detection using SVM and reached an accuracy of 93.5%. 



