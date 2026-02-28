# autonomous-rc-sim

High-speed autonomous RC car simulation built in NVIDIA Isaac Sim.
Target: 160km/h+ vehicle control using reinforcement learning.

## Description
This project simulates a high-speed autonomous RC car from the ground
up using NVIDIA Isaac Sim and Isaac Lab. The base platform is an Arrma
Limitless roller — a 1/7 scale speed run chassis capable of 160km/h+ —
with a fully custom body redesign to house the autonomous systems stack.

The goal is to build a complete simulation pipeline — physics model,
sensor suite, domain randomization, and RL training — then transfer
the learned policy to the real hardware platform.

All technical decisions, dead ends, and breakthroughs are documented
publicly as the project progresses.

## Goals
- Accurate vehicle dynamics model (suspension, tire friction, Ackermann steering)
- Custom body design to house compute, sensors, and electronics
- Sensor suite: LiDAR, camera, IMU, real-time ESC telemetry
- Domain randomization for sim-to-real transfer
- Trained RL control policy capable of stable high-speed navigation
- Real-world validation on the physical Arrma Limitless platform

## Tech Stack
- NVIDIA Isaac Sim / Isaac Lab
- PhysX 5 vehicle dynamics
- Python
- Reinforcement learning (library TBD)

## Hardware
- Arrma Limitless Roller (1/7 scale, speed run platform)
- Custom autonomous systems body (in design)
- LiDAR, camera, IMU
- ESC with real-time telemetry

## Dev Log
### Week 1 — Project initialized
- Defined project scope and simulation architecture
- Repository created, planning phase underway

## Status
🟡 In Progress — Week 1
