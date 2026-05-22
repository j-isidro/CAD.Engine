# 3D Printed Engine 

## Project Overview
This project involved the comprehensive design, analysis, and fabrication of a 1:7 scale internal combustion engine model. Working in a three-person team, we designed a crankshaft-piston assembly from scratch, performed thermodynamic and dynamic analysis, 3D printed all components in PLA, and competed against other teams in a formal RPM competition — **winning with a maximum rotation rate of 2,100 RPM**.

The engine was evaluated against the 2012 Ford Coyote 5.0L V8 using a power-to-size scoring formula, with the goal of maximizing horsepower and torque relative to engine volume.

### Final Assembly without the legs

<img src="https://github.com/user-attachments/assets/146a6d67-536c-49fe-a2d9-02339d61c661" 
  width="360" 
  height="420" 
  alt="IMG_7209" />


---

## Objectives
- Analyze thermodynamic principles to determine optimal piston diameter, stroke length, and cylinder count
- Design a full crankshaft-piston assembly in SolidWorks including pistons, connecting rods, crankshaft, and engine block
- Perform SolidWorks motion simulation to generate velocity, acceleration, and displacement graphs
- Validate simulation results with hand calculations and free-body diagrams
- Conduct stress analysis on the connecting rod to determine factor of safety and optimal material selection
- Fabricate all components using PLA filament on Prusa 3D printers
- Survive a formal staged RPM test (300 → 600 → 900 RPM, then incrementally increased to failure or limit)

---

## Tools & Software
- **SolidWorks** — Part modeling, full assembly, motion simulation, stress analysis
- **Prusa Core One** — PLA filament 3D printing
- **Hand calculations** — Thermodynamic analysis, dynamic validation, stress and strain
- **High-RPM electric motor** — Formal competition testing apparatus

---

## Design Constraints
- Scale: 1:7 (must fit within a 2012 F-150 engine bay at scale)
- Max model size: 131 mm × 131 mm × 102 mm
- Min model size: 80 mm × 80 mm × 80 mm
- Bore: ≥ 13 mm diameter (1:7 scale)
- Stroke: ≥ 13 mm (1:7 scale)
- Max compression ratio: 14:1
- Material: PLA only, all hardware must be 3D printed
- Engine configuration: Must differ from V8, Flat 8, or Rotary

---

## Engineering Process

### Phase 1: Thermodynamic Analysis
- Calculated optimal bore, stroke, compression ratio, and piston count
- Determined horsepower and torque per piston and for the full engine
- Benchmarked theoretical performance against the 2012 Coyote 5.0L V8

### Phase 2: CAD Assembly
- Modeled all individual components in SolidWorks: pistons, connecting rods, crankshaft, connecting pins, and engine block
- Designed functional dynamic mates to simulate realistic engine motion
- Ensured crankshaft interface matched the competition testing device

### Phase 3: Motion Simulation & Hand Calculations
- Ran SolidWorks motion analysis to generate velocity, acceleration, and displacement graphs for the piston head
- Completed hand calculations for validation including free-body diagrams and kinetic diagrams for the crankshaft-piston assembly

### Phase 4: Stress Analysis
- Determined stress, strain, and factor of safety on the connecting rod at the piston head location
- Used results to justify material selection and identify design changes before printing

### Phase 5: Fabrication & Optimization 
Three major design iterations were completed before the final competition build:

**Iteration 1**
- Multiple failure points identified during informal testing
- Issues with cylinder fitment, crankshaft geometry, and mounting

**Iteration 2**
- Redesigned crankshaft using fused separate pieces
- Crankshaft fusion resolved some issues but mounting remained problematic

**Final Iteration**
- Squared crankshaft pins added to resist rotation and withstand torsional stress
- Crankshaft printed in separate parts proved efficient and effective
- Engine still experienced some connecting rod fusion during high-RPM testing

---

## Testing & Results
- **Formal test protocol:** Sustained 300 RPM for 30s → 600 RPM for 30s → 900 RPM for 60s
- **Maximum RPM achieved: 2,100 RPM** — highest in the class
- **Result: 1st place** in the formal engine competition
- Engine ultimately failed due to fusion of a connecting rod to the crankshaft, not wrist pin failure
- **Future improvement identified:** dried super glue between connecting rod and crankshaft to reduce friction and prevent fusion

[Watch the engine run at 900 RPM](https://drive.google.com/file/d/1uopaTeMAg6DidHOojKf3JH2RAt3dzKZa/view?usp=drive_link)
---

## Skills Demonstrated
- SolidWorks (part modeling, assemblies, motion simulation, stress analysis)
- Thermodynamic and dynamic engineering calculations
- 3D printing and iterative design
- Technical communication (poster presentation in class)
[Engine Project Poster.pdf](https://github.com/user-attachments/files/28160630/Engine.Project.Poster.pdf)


<img src="https://github.com/user-attachments/assets/cbc64d0f-450a-4240-990b-fa3b3ffd28bb"
  width="360" 
  height="420" 
  alt="IMG_4467" />
