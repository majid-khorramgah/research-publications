# Low-Latency Full-Body Motion Reconstruction from Sparse IMUs with Human Shape-Aware Deep Learning

**Journal:** Robotics and Autonomous Systems
**Manuscript Number:** ROBOT-D-26-02661
**Status:** Under Review

**Corresponding Author:** Hassan Nosrati

**Authors:**
Hassan Nosrati; Majid Khorramgah; Mojtaba Rahemi; Amir Hossein Ahmadi

## Overview

Sparse inertial measurement units provide a practical and scalable solution for human motion capture in real-world environments, but they introduce challenges related to latency, accuracy, and incomplete observation. This study proposes a fast full-body motion reconstruction framework using only **six IMUs** while explicitly considering human body shape.

The proposed **Fast Inertial Poser** employs a recurrent neural network architecture organized according to the human kinematic tree, enabling efficient motion estimation without dependence on future frames. Body shape information is incorporated into the reconstruction process, while separate upper-body and lower-body estimation modules improve computational efficiency.

A single-frame inverse kinematics solver is subsequently used to recover joint rotations. The reported performance of **65 frames per second with 15 ms latency on embedded hardware** demonstrates the potential of the approach for real-time applications.

The work is particularly relevant to **Human Motion Understanding, 3D Vision, Robot Perception, and Embodied AI**, with potential applications in wearable motion capture, teleoperation, virtual reality, and humanoid robot control.

## Research Areas

`Human Motion Reconstruction` · `Sparse IMU` · `3D Human Pose` · `Deep Learning` · `Robot Perception` · `Embodied AI` · `Real-Time Motion Capture`
