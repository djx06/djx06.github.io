---
title: "Smart Frisbee: Analyzing Data on Throws, Catches, and Player Performance Using BLE and IMU on a Frisbee and Wristbands"
excerpt: "The Smart Frisbee project aims to address the limitations of traditional Ultimate Frisbee games by utilizing Bluetooth and IMU sensors in a smart frisbee and wristbands to collect and analyze data on throws, catches, and player performance. This data will be used to provide automated tracking, feedback, and analysis capabilities, enabling players to identify areas for improvement and enhance their gameplay experience.<br/><img src='/images/smartfrisbee/intro.png'>"
collection: portfolio
---

The Smart Frisbee project is designed for players and enthusiasts of Ultimate Frisbee who seek to enhance their gameplay experience, receive feedback on their performance, and improve their skills. This includes players of all ages and skill levels, as well as coaches and trainers who work with Ultimate Frisbee teams to develop effective training programs.

# Features
* Automated tracking and analysis of throws,
catches, and player performance.
* Real-time feedback for winning players.
* Cloud-based storage for data access and
sharing among players and coaches.
* Enhanced gameplay experience with
accurate point counting.

# Implementation
### Hardware
<img src='/images/smartfrisbee/hw_diagram.jpeg'>

### Software
<img src='/images/smartfrisbee/sw.png'>

# My Contributions
* Built wristband prototypes that detected users’ hand motion via IMU and sent data to a frisbee through BLE.
* Built a frisbee prototype with an on-chip SVM model to classify the quality of a throw based on IMU data from both the frisbee and the wristband. The frisbee sent history data to Firebase through an Android app.
* Supported BLE data transmission with multiple peripherals and the frisbee played a dual role.

