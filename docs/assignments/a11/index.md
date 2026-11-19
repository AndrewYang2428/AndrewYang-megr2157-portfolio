# A11 – Motor Selection

## Description:
A tensile tester is a mechanical testing device used to measure how materials respond to uniaxial tension. It applies a controlled pulling force to a specimen while recording the resulting elongation, allowing engineers to determine properties such as yield strength, ultimate tensile strength, and elongation at break. This data is essential for understanding a material’s mechanical behavior and suitability for design applications.

## Objective

Part 2 Scope of Work
- Select a Motor
- Design Motor Mounts
- Select or design a coupler
- Design a Frame to support a crosshead stability and tensile load
- Select or design a Clamp Analysis and Design
- Provide complete CAD model of the engineered parts of the Tensile Tester
- Deliver a Bill of Materials and Engineering Cost

Key Constraints:
- No electronics, no software: purely mechanical.
- Load capacity: 2 kN (with appropriate safety factor in structure and drivetrain).
- Speed range: 1–50 mm/min (achieved via screw lead selection).
- Form factor: bench-top footprint favored; manageable overall height; 18 inch leadscrew minimum.
- Safety Factor: 4

## Design Floating Bearing Mount:

#### Andrew's Part:

### RC3 Clearance Fit Class Research:

Looking in the Machinery Handbook, I found that the RC3 Clearance Fit of the floating bearing mount has to be +0.5/0 based on the diameter of the Leadscrew. The diameter that was calculated for the 0.146 in., so the RC3 fit is +.151 in. With this tolerance, there were not any specific floating bearing mounts that fit this specification perfectly but there was one floating bearing mount that would work best for our design, which was the "End Supports for Ball Screws and Precision Lead Screws", Part#: 60755k12, on McMaster-Carr.

<p align = 'center'>
<img width="3086" height="3500" alt="RC3 " src="https://github.com/user-attachments/assets/cb2ab778-5a20-4259-9d98-483eeb16cc2b" />
</p>
<p align = 'center'>
<img width="1907" height="865" alt="FloatingBearingMount" src="https://github.com/user-attachments/assets/c95d2c54-fb01-47c0-aed8-49a85250f913" />
</p>

### RC3 Clearance Fit:

#### [Floating Bearing Mount CAD File](60755K12_FloatingBearingMount.SLDPRT)

#### Ideal Fit:

<p align = 'center'>
<img width="49.5%" height="1017" alt="IdealFit" src="https://github.com/user-attachments/assets/75523d83-f419-450f-bdcb-0413da390586" />
<img width="49.5%" height="1020" alt="IdealFitSketch" src="https://github.com/user-attachments/assets/23a4a895-96a2-4ad5-b3b8-dc617817d89c" />
</p>

#### Chosen Fit:

<p align = 'center'>
<img width="49.5%" height="1017" alt="ChosenFit" src="https://github.com/user-attachments/assets/c9f80940-7e0a-407d-b199-3a05d13e5a6f" />
<img width="49.5%" height="1017" alt="ChosenFitSketch" src="https://github.com/user-attachments/assets/466fd8c3-57a1-426d-a95b-da230b57d50e" />
</p>

## [Bill of Cost](Bill_of_Cost.pdf)

<p align = 'center'>
<img width="387" height="552" alt="BillofCost1" src="https://github.com/user-attachments/assets/98fa6cef-b353-4525-8a95-7ab04e50c474" />
</p>
<p align = 'center'>
<img width="387" height="80" alt="BillofCost2" src="https://github.com/user-attachments/assets/78805633-37ff-4a6f-b9c0-9383767b9212" />
</p>

## Lessons Learned:

#### Andrew's Lessons Learned:

For Part 2 of this project, I learned that there are certain parts that won't fit correctly to your specifications, but you have to choose something that comes close to what was calculated. I was not able to find a specific floating bearing mount that had the correct clearance that would work perfectly with what we calculated the Leadscrew diameter to be, but the one chosen was close enough to what we calculated, and it gave an estimated price as well. I learned that with these designs and models, the price for these projects can increase pretty fast. It is important to keep a "Bill of Cost" to keep track of the amount of money it will take if we were to follow through with this design. It will also help us stay within the range of the budget for the project. When working in a team, we have to take into account our team's work and make adjustments that will fit what they have as well.

## 2157 Section: Designed Part Drawings

#### Andrew's Part:

### [Crosshead Drawing](crosshead.SLDDRW):

<img width="1917" height="1020" alt="Crosshead Drawing" src="https://github.com/user-attachments/assets/e195afb0-0874-4a0b-8c43-4a632975406d" />

### [Motor Bracket Housing](motor bracket housing.SLDDRW):

<img width="1917" height="1020" alt="MotorBracketDrawing" src="https://github.com/user-attachments/assets/4580d638-35ca-4e03-8a91-35d5ba2100df" />

### [Floating Bearing Mount](60755K12_Floating Bearing Mount.SLDDRW):

<img width="1917" height="1020" alt="FloatingBearingMountDrawing" src="https://github.com/user-attachments/assets/a11147d2-3e2b-4309-80d8-9d76cc3e513c" />














