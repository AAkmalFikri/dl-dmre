# Decentralized Dual-Layer Multi-Robot Exploration

### Predictive Area Division and Redundancy-Aware Waypoint Sequencing

This repository contains a **ROS 2-based decentralized multi-robot exploration system** that investigates a dual-layer strategy combining predictive area division and redundancy-aware waypoint sequencing under distance-limited peer-to-peer communication.

Each robot independently performs mapping, exploration planning, and navigation using locally available information and data exchanged with connected peers.

## Key Features

- **Predictive Area Division (B-FAME):** Allocates approximately balanced and connected exploration regions.
- **Adaptive Map Downsampling:** Reduces the computational cost of repeated area division.
- **Redundancy-Aware Waypoint Sequencing:** Uses Simulated Annealing (SA) to optimize frontier waypoint sequences while considering peer commitments.
- **Communication-Aware Coordination:** Adapts region allocation and waypoint planning to communication availability.
- **Decentralized Architecture:** Supports independent exploration without a central task allocator.

## System Overview

The system integrates **ROS 2, RTAB-Map, and Nav2**, with RGB-D cameras providing environmental observations for mapping and exploration.

The exploration strategy is evaluated in simulated warehouse environments with teams of **2–4 robots** under range-limited communication.

## Publications

**Fikri, A. A., & Matsunaga, N. (2025).** B-FAME: An adaptive area division algorithm for multi-robot exploration and mapping. *IEEE ARSO 2025.*

https://doi.org/10.1109/ARSO64737.2025.11124985

**Related journal manuscript:** In preparation.

## Repository Status

🚧 **Under Development — Preparing for Public Release**

The source code, installation instructions, simulation configurations, and experimental documentation are being prepared for public availability.

## Authors

Achmad Akmal Fikri & Nobutomo Matsunaga  
Kumamoto University, Japan
