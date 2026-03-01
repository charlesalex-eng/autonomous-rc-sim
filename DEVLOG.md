# Dev Log

## Week 1 — Feb 28, 2025

### What I did
- Initialized repository
- Researched hardware stack
- Read Isaac Lab vehicle documentation

### Decisions made
- Hardware Choices
    - MGM: industrial grade controller and full data logging
    - Lehner: monstruous power (easily capable of reaching the desired speed, also got a good deal combo with MGM)
    - Jetson: considered other options (Pi w/ ai Hat+ 2), but realistically the best option for the needed compute.
    - Oak-d lite: onboard depth perception and AI (reduces the compute required by the jetson)
    - Lidar: need to reconsider RPLidar S2, the optimal and safe detection range needs to be 130m+ (to account for breaking + reaction distance).

- Car Specs
    - Length: 730mm
    - Width: 310mm (tire to tire, trackwidth)
    - Height: 165mm (this will be higher since I'm making a custom body)
    - Wheelbase: 406mm
    - Ground Clearance: 15mm

### Open questions
- What RL library to use
- How to handle tire friction model

### Next week
- Find Arrma Limitless exact specs
- Begin Isaac Sim environment setup