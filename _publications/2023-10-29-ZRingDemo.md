---
title: "Demo of Z-Ring: Context-Aware Subtle Input Using Single-Point Bio-Impedance Sensing. (Best Demo)"
collection: publications
permalink: /publication/2023-10-29-zringdemo
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2023-10-29
venue: 'UIST'
paperurl: 'http://djx06.github.io/files/paper4_ZRingDemo.pdf'
citation: 'Anandghan Waghmare, Jiexin Ding, Ishan Chatterjee, and Shwetak Patel. 2023. Demo of Z-Ring: Context-Aware Subtle Input Using Single-Point Bio-Impedance Sensing. In Adjunct Proceedings of the 36th Annual ACM Symposium on User Interface Software and Technology (UIST 23 Adjunct). Association for Computing Machinery, New York, NY, USA, Article 79, 1–3.'
---
<!-- This paper is about the number 3. The number 4 is left for future work. -->

This paper presents Z-Ring, a novel wearable device that uses radio frequency (RF) based sensing to offer unique capabilities for human-computer interaction, including subtle input, object recognition, user identification, and passive surface interaction. With only a single sensing modality, Z-Ring achieves diverse and concurrent interactions that can enhance the user experience. We illustrate the potential of Z-Ring to enable seamless context-aware interactions via a custom music player application. In the future, we plan to expand Z-Ring’s functionality with user customization and explore usage for additional applications.

My contributions:
* Implemented the BLE transmission and acoustic data reading from the contact microphone on Seeed Xiao.
* Built a CNN+LSTM model to detect mircogestures. It achieved a gesture recognition accuracy of 92.7% across sessions and an accuracy of 84.0% across users, rising to 93.0% with four gesture examples.
* Detected index finger rubbing against a surface by a multithreaded application to enable on-surface tracking.


[Download paper here](http://djx06.github.io/files/paper4_ZRingDemo.pdf)

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->