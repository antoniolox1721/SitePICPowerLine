---
title: "Live Video Feed Enhancement: Real-Time Inspection Monitoring"
date: 2025-05-18T16:15:00+01:00
image_webp: images/blog/live-video.webp
image: images/blog/live-video.jpg
author: António Alves
description: "Luís Almeida has integrated an enhanced live video system that supports real-time inspection monitoring with multiple viewing options."
---

# Real-Time Monitoring: Enhanced Live Video System

Our inspection platform now features a dramatically improved live video system thanks to the work of **Luís Almeida**. This enhancement allows operators to see exactly what the drone sees in real-time, making inspections more interactive and effective.

## Crystal-Clear Live Feed

The new video implementation offers:

- **High-definition streaming** directly from the drone camera
- **Low-latency transmission** for responsive control
- **Automatic orientation adjustment** based on drone position
- **Picture-in-picture capability** for monitoring multiple views
- **Support for both portrait and landscape orientations** on control devices

## Multiple View Options

Operators can now switch between different camera views during a mission:

- **Primary camera** for detailed inspection imagery
- **Secondary/FPV camera** for situational awareness
- **Split-screen mode** to monitor both simultaneously

This flexibility allows inspection teams to maintain both detailed views of structures and broader awareness of the drone's surroundings.

## Technical Implementation

The live video system leverages the DJI SDK's `VideoFeeder` module to access and process video streams directly from the drone. The implementation includes:

- Custom `VideoFeedView` class for rendering the video
- Orientation-responsive layouts that adapt to device rotation
- Efficient memory management for smooth performance
- Support for recording streams for later review

## Real-World Benefits

This enhanced video capability has already proven valuable in field testing:

- Inspectors can make real-time decisions about areas needing closer examination
- Remote experts can join inspection sessions via shared video feeds
- Training new operators is easier with the ability to observe exact drone perspectives
- Documentation is improved with synchronized video recording

## Coming Soon

We're working on adding augmented reality elements to the video feed that will overlay structural information, measurement tools, and inspection checklists directly onto the live view.

The improved live video system makes a substantial difference in the immediacy and effectiveness of drone inspections. Well done, Luís!