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
    - Width: 310mm (tire to tire, trackwidth) technically has a 2mm delta front/back, back = 312mm
    - Height: 165mm (this will be higher since I'm making a custom body)
    - Wheelbase: 406mm
    - Ground Clearance: 15mm
    - Tires (toyo proxes replicas)
        - Front width: 42mm
        - Front diameter: 100mm
        - Rear width: 53mm
        - Rear diameter: 107mm
    - Front hub height: 41.3mm
    - Rear hub height: 28.6mm
        - 12.7mm chassis rake for speedruns

- Importing URDF to USD (fusion 360 -> Isaac SIM format)
    - video: https://www.youtube.com/watch?v=AMfEtZ4hyLY

### Open questions
- What RL library to use
- How to handle tire friction model

### Next week
- Find Arrma Limitless exact specs
- Begin Isaac Sim environment setup