# 2022HackKings_Mo-Choo
**Winner of 2022 HackKing’s Technical Challenge by BlackRock**

This hackathon was held by KCL Tech Society and sponsored by BlackRock. Our team and I developed Mo-Choo, which is augmented reality interface to transform devices into touch less screens by using Computer Vision Technology as well as Machine Learning Models. Mo-Choo was selected as a winner by BlackRock.

# About Mo-Choo
In the wake of the global pandemic, healthcare workers have been stretched thin, with increased stress, risks of infection, and workload taking a toll on their well-being. Mo-Choo aims to alleviate some of these challenges while introducing benefits for a wider audience, including those with speech and hearing impairments.

## Problem Statement

Healthcare workers, particularly nurses, are grappling with occupational burnout due to several factors:

- Increased exposure to contagions
- Lack of sufficient protective equipment
- High amount of time spent on non-nursing tasks such as paperwork

According to a report by WHO on October 5, 2022:
- 23-46% of healthcare workers experience anxiety
- 21-37% suffer from depression

Additionally, people with speech and hearing impairments often find it difficult to engage with technologies such as drive-throughs that primarily rely on voice-based interaction.

## Our Solution

Mo-Choo introduces a real-time hand gesture recognition interface to combat these challenges. This touchless interface allows healthcare workers and others to interact with digital devices without physically touching them, which is especially beneficial in hygiene-sensitive environments.

### How It Work

Built using Python, OpenCV, MediaPipe, and TensorFlow
Recognizes 9 essential hand gestures: 'okay', 'stop', 'peace', 'call me', 'fist', 'rock', 'smile', 'thumbs up', 'thumbs down'
These gestures serve as intuitive commands, streamlining user interaction with devices.

### Features

- Real-time Touchless Gesture Recognition: Interact with devices without physical contact
- Enhanced Hygiene and Reduced Infection Risk: Especially useful for healthcare and other hygiene-sensitive industries
- Gesture Commands: Easy-to-understand gestures that are recognized in real-time for quick actions
- Accessibility: Makes technology more accessible for people with speech and hearing impairments (eg.drive-throughs)

## Technologies Used

- Python: For backend development
- OpenCV: Real-time computer vision and image processing framework
- MediaPipe: Open-source, lightweight machine learning framework by Google for customized solutions
- TensorFlow: Pre-trained models for gesture recognition

# Demo

https://youtu.be/KFnQ5QgkdNY

# Bibliography

- Thanks to [Tech-Vidvan](https://techvidvan.com/tutorials/hand-gesture-recognition-tensorflow-opencv/) for the tutorial and base source code
- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) to understand the algorithm
