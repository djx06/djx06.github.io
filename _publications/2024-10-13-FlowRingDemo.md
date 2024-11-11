---
title: "Demo of FlowRing: Seamless Cross-Surface Interaction via Opto-Acoustic Ring."
collection: publications
permalink: /publication/2024-10-13-flowringdemo
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2024-10-13
venue: 'UIST'
paperurl: 'http://djx06.github.io/files/paper5_FlowRingDemo.pdf'
citation: 'Jiexin Ding, Ishan Chatterjee, Alexander Ching, Anandghan Waghmare, and Shwetak Patel. 2024. Demo of FlowRing: Seamless Cross-Surface Interaction via Opto-Acoustic Ring. In Adjunct Proceedings of the 37th Annual ACM Symposium on User Interface Software and Technology (UIST Adjunct 24). Association for Computing Machinery, New York, NY, USA, Article 40, 1–3.'
---
<!-- This paper is about the number 3. The number 4 is left for future work. -->

We demonstrate FlowRing, a ring-form-factor input device that enables interaction across a range of ad-hoc surfaces including desks, pants, palms and fingertips with seamless switching between them. This versatility supports systems that require both high precision as well as mobile control, such as mobile XR. FlowRing consists of a miniature optical flow sensor, skin-contact microphone, and IMU, providing a unique ergonomic design that rests at the base of the finger like conventional jewelry. We show the potential of FlowRing to enable precise control of interfaces on available surfaces via music player application and whiteboarding application.

My contributions:
* Implemented the BLE transmission and acoustic data reading from the contact microphone on Seeed Xiao.
* Built a CNN+LSTM model to detect mircogestures. It achieved a gesture recognition accuracy of 92.7% across sessions and an accuracy of 84.0% across users, rising to 93.0% with four gesture examples.
* Detected index finger rubbing against a surface by a multithreaded application to enable on-surface tracking.


[Download paper here](http://djx06.github.io/files/paper5_FlowRingDemo.pdf)

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->