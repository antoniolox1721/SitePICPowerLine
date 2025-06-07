---
title: "Safety First: New Obstacle Avoidance System in Testing"
date: 2025-05-15T11:45:00+01:00
image_webp: images/blog/obstacle-avoidance.webp
image: images/blog/obstacle-avoidance.jpg
author: António Alves
description: "António Alves has implemented advanced obstacle detection and avoidance capabilities to ensure safer automated inspections."
---

# Enhancing Safety with Advanced Obstacle Avoidance

Safety is always our top priority, which is why we're excited to announce that **António Alves** has successfully implemented and tested a comprehensive obstacle avoidance system for our drone inspection platform.

## Multi-Directional Obstacle Detection

The new system leverages the drone's built-in sensors to detect obstacles in multiple directions:

- Forward-facing detection for flight path obstacles
- Upward detection for overhead obstructions
- Omnidirectional sensing during critical maneuvers

Real-time distance measurements are continuously monitored and displayed in the mission control interface, giving operators full awareness of the drone's environment.

## Intelligent Avoidance Behaviors

When an obstacle is detected, the system can:

1. **Automatically pause** the current mission
2. **Alert operators** with detailed information about the obstacle's location and distance
3. **Suggest alternative paths** when available
4. **Enable safe manual intervention** when necessary

## Technical Implementation Details

The implementation integrates directly with the DJI SDK's `FlightAssistant` module, specifically utilizing:

- `setCollisionAvoidanceEnabled()` for general collision protection
- `setUpwardVisionObstacleAvoidanceEnabled()` for overhead obstacles
- `setRTHObstacleAvoidanceEnabled()` for safe return-to-home functionality
- `setLandingProtectionEnabled()` for secure landing operations

The system also includes a visual reporting component that shows operators the closest obstacles and their distances in meters, as well as providing warning levels (None, Warning, Serious) for each detected sector.

## Testing Results

Initial testing in controlled environments has shown excellent results, with the system successfully detecting and avoiding obstacles as small as 30cm in diameter. The integration is seamless with our existing mission planning and execution workflows.

## Future Development

We're continuing to refine the system with more advanced avoidance strategies, including adaptive path planning that can automatically route around obstacles while still completing inspection objectives.

This obstacle avoidance system represents a significant advancement in the safety and reliability of our automated inspection platform. Kudos to António for his excellent work on this critical safety feature!