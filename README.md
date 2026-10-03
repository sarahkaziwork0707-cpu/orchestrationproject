# LiDAR-Enabled Swarm Orchestration for Disaster Relief

## Overview
This interactive prototype demonstrates an AI-powered rescue mission orchestration platform that integrates LiDAR-SLAM collaborative mapping with dynamic resource allocation for disaster relief operations.

## Key Features

### Spatial Intelligence Layer (LiDAR-SLAM)
- Real-time LiDAR point cloud visualization
- Collaborative multi-agent infrastructure mapping
- Semantic map layer (free space, debris, unexplored zones, hazard regions)
- Shared global rescue map fusion

### Mission Orchestration Layer
- Dynamic task allocation based on capability, battery, location, and communication quality
- Autonomous re-planning when routes become blocked
- Communication-aware relay repositioning
- Battery-aware reserve drone swap protocol
- Human-in-the-loop escalation capability

### Resource Allocation Layer
- Real-time inventory tracking (Medical Kits, Food, Water)
- Zone-priority-based allocation engine
- Dynamic demand evaluation
- Insufficient inventory detection and warning
- Blockchain-verified transparent delivery ledger

## How to Use
1. Open `index.html` in any modern web browser
2. Observe the initial swarm deployment and LiDAR mapping
3. Click **"Simulate Debris (Blocked Route)"** to trigger dynamic re-planning
4. Click **"Simulate Battery Depletion"** to trigger reserve drone swap
5. Click **"Simulate New High-Priority Demand"** to trigger resource re-allocation
6. Click **"Reset Simulation"** to restart

## Technologies Demonstrated
- LiDAR-SLAM mapping concept
- Collaborative multi-robot mapping
- Semantic map representation
- Dynamic task allocation algorithm
- Resource allocation engine with priority weighting
- Blockchain ledger simulation
- Real-time telemetry visualization

## Alignment with Problem Statement
This prototype addresses the core requirements of:
- EL-05: AI-Powered Autonomous Robot & Drone Swarm Mission Orchestration
- EL-03: Intelligent and Transparent Disaster Relief Resource Allocation

## Note
This is a high-level logic simulation demonstrating the orchestration and allocation algorithms. The production system would integrate with ROS 2, Gazebo, SLAM Toolbox, and Nav2 for real-world deployment.
