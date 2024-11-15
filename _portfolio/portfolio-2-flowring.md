---
title: "FlowRing: Integrating Microgestures and Surface Interaction for Seamless XR Input"
excerpt: "FlowRing enables both quick, discreet in-air microgestures (left) and precise on-surface interactions (right), allowing for always-available, ad-hoc interactions. Such a peripheral could control wearable devices quickly like changing earbud volume while on-the-go or be used to control an immersive desktop environment in a mixed reality headset.<br/><img src='/images/flowring/intro.png'>"
collection: portfolio
---

Microgestures offer an excellent solution for on-the-go scenarios, enabling discreet and subtle input in motion-rich environments. In contrast, immersive experiences like desktop require high-precision continuous pointing and selection. As lightweight AR (North Focals, Oppo Air Glass 2) and productivity-oriented VR (Meta Quest Pro, Apple Vision Pro) slowly converge, future devices may require both interaction paradigms. To bridge this gap, we introduce FlowRing, a novel ring wearable that supports both in-air gestures (four cardinal direction swipes and taps) and precise on-surface 2D continuous interactions using an optical flow sensor, skin-contact microphone, and IMU. In a user study involving 13 participants, FlowRing achieved a gesture recognition accuracy of 92.7% across sessions and an accuracy of 84.0% across users, rising to 93.0% with four gesture examples. A separate study involving a 2D Fitts law test demonstrated the system's effectiveness for continuous input tasks. This paper comprehensively describes the FlowRing device, its sensing capabilities, the evaluation studies, and the exciting possibilities it opens up for future interaction scenarios.

# Motivation
FlowRing enables both quick, discreet in-air microgestures (left) and precise on-surface interactions (right), allowing for always-available, ad-hoc interactions. Such a peripheral could control wearable devices quickly like changing earbud volume while on-the-go or be used to control an immersive desktop environment in a mixed reality headset.
<img src='/images/flowring/intro.png'>

# Contributions
* We develop FlowRing, a wireless ring device with optical flow, a contact microphone, and an IMU that enables both on-the-go subtle input and in-situ expressive input.
* We build a hardware and software pipeline to collect, evaluate, and validate interaction data.
* A 13-person user study demonstrating the effectiveness of FlowRing’s microgesture input capabilities across users with different hand sizes and skin tones and a Fitts’ evaluation of continuous 2D surface interaction.
  
# Method
### High-level State Architecture
A gating classifier rejects false positives from daily tasks and determines if the user performed a gesture or is holding their hand in a mouse-like configuration over a surface. If it is a gesture, the discrete gesture classifier then determines the type of gesture. If it is a mouse-like action, the gating model then can engage a continuous 2D on-surface tracking scheme.
<img src='/images/flowring/states.png'>

### Mouse State of 2D Surface Tracking
State diagram of 2D surface interaction for cursor control. Transition conditions are listed next to the arrows.
<img src='/images/flowring/cursor_state_diagram.png'>

### Gating Model & Discrete Gesture Classification
This model contains 3 2D CNN layers followed by a MaxPooling layer and an LSTM layer. Then the fully connected layer and softmax are applied.
<img src='/images/flowring/gesture_processing.png'>
<img src='/images/flowring/gesture_model.png'>

# Results
FlowRing achieved a gesture recognition accuracy of 92.7% across sessions and an accuracy of 84.0% across users, rising to 93.0% with four gesture examples.
