# A10 – Lead Screw Design Part I

## Description:

A tensile tester is a mechanical testing device used to measure how materials respond to uniaxial tension. It applies a controlled pulling force to a specimen while recording the resulting elongation, allowing engineers to determine properties such as yield strength, ultimate tensile strength, and elongation at break. This data is essential for understanding a material’s mechanical behavior and suitability for design applications.

Design and build a mechanically driven tensile tester capable of applying up to 2 kN axial tensile load with a controllable crosshead speed from 1 to 50 mm/min. Each team is responsible for the mechanical components outlined below. The system will provide consistent, well-aligned loading for polymers and light metals, suitable for instructional use and basic materials evaluation.

## Objective: Part 1 Scope of Work

- Develop a lead-screw–driven crosshead 
- Ensure accurate, repeatable load application to 2 kN with minimal crosshead deflection and misalignment.
- Provide robust specimen gripping, simple calibration provisions (mechanical), and safe, ergonomic operation.
- Key Constraints
- No electronics, no software: purely mechanical.
- Load capacity: 2 kN (with appropriate safety factor in structure and drivetrain).
- Speed range: 1–50 mm/min (achieved via screw lead selection).
- Form factor: bench-top footprint favored; manageable overall height; 18-inch leadscrew minimum.
- Safety Factor: 4

## Design the Crosshead:

### Beam Stress/Strength Analysis:

<img width="2633" height="3500" alt="IMG_1" src="https://github.com/user-attachments/assets/d06767e0-5339-40d6-8fc4-feb468410b30" />
<img width="2589" height="3500" alt="IMG_2" src="https://github.com/user-attachments/assets/349469b1-7cb2-40de-ad4d-8684460b3c91" />

### Beam Deflection:

<img width="2563" height="3500" alt="IMG_3" src="https://github.com/user-attachments/assets/a6efb431-332c-474e-b580-88f692c24888" />
<img width="2563" height="3500" alt="IMG_4" src="https://github.com/user-attachments/assets/8fe7fd28-3439-4efe-a6ab-96c806b65926" />

### Multiview Sketch:

<img width="2660" height="3500" alt="IMG_5" src="https://github.com/user-attachments/assets/20a2c3a5-aa49-44fc-b3e2-9f78853b1c27" />

## Lessons Learned:

For this project, I was assigned to design the Crosshead of the Tensile Tester. For the Crosshead, I had to use the Stress/Strength Analysis and the Beam Deflection Analysis to calculate the parameters of the Crosshead as well as the material for the Crosshead. With this, I had to calculate for the height of the Crosshead using the Stress/Strength equation and the Deflection equation. By using these equations, I learned to make assumptions to get to a estimated calculation that fit the given parameters. To ensure that my calculations were correct, my team and I ran simulations on the Tensile Tester to test the Crosshead, making sure it worked properly. The FEA simulation shows what needs to be changed in the design to fit the parameters. I learned that the first simulation will most likely not work and changes will need to be made. I learned that projects like this will have trial and errors until there is a final solution that fits the constraints. 

## 2157 Students Only:

### [Crosshead Drawing:](crosshead.SLDDRW)

<img width="1917" height="1020" alt="Crosshead_Drawing" src="https://github.com/user-attachments/assets/f26aefee-fa77-4dc1-b47b-459bf43fcdb4" />



















