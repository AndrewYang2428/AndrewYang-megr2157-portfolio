# A3 – Parametric and FEA

## Objective

- Use axial deflection modeling to design its dimensions
- Use parametric design to determine a bars length
- Introduce you to FEA (Finite Element Analysis)
- Introduce you to linking dimensions to appropriate parameters in CAD.
- Compare and contrast the different analysis

## Outline:

<img width="3500" height="2333" alt="IMG_7826" src="https://github.com/user-attachments/assets/f5d3b357-51ae-4085-be27-d2a2d479e7a2" />

Before starting the CAD model of the bar, I wrote down the knowns and unknows of this project to get a clear understanding about what we knew and what we needed to solve for. For this project, we had to solve for the length of the bar. With the dimensions, it came out to be 44.21 inches. 

<img width="875" height="736" alt="A3_Dimensions" src="https://github.com/user-attachments/assets/c3acdf49-3943-455c-be50-02db22f7d1f5" />

The diameter that I used to solve for the area and length of the aluminum bar was 0.5inches. After making a global variable for the diameter, I was able to plug this value into the equation table I was able to calculate the area of the aluminum bar. 

<img width="1242" height="826" alt="A3_Equations" src="https://github.com/user-attachments/assets/b1c5e649-f30a-4453-8b17-ef7c1197d8e2" />

The equation table in SolidWorks shows all of the global variables I had to create to calculate the length or depth of the bar. This made calculating the length or depth of the aluminum bar easy because all we had to do was plug in the formula to solve for the missing variable. If there are any changes that are needed to be made, we could simply change the values in this table to get new calculations and plug them in for where they were changed. 

<img width="1917" height="1020" alt="A3_Thickness" src="https://github.com/user-attachments/assets/2f9ff3a2-f90d-4dd7-b61c-d1696e33d38a" />

Once the length or depth of the aluminum bar was calculated in the equation table, I could plug that value in to make the actual aluminum bar. This shows the actual length of the bar with the parameters that were given at the beginning of the project. 

## Finite Element Analysis(FEA) on Aluminum Bar:

### Simulation:

With little knowledge working in SolidWorks and working with simulations, I had to learn how to move around pretty quickly to complete this section of the project. SolidWorks is pretty easy to navigate through so eventually I was able to make my aluminum bar for the simulation testing.

<img width="1917" height="1021" alt="A3_Fixture" src="https://github.com/user-attachments/assets/c24a2ed8-15db-4171-be02-47afe5f21d11" />

In this step of the simulation, the fixture stops the object from moving in open space. There are forces acting on it from the (x, y, z) planes to keep the object from moving. Once you have selected a surface of the object to hold down, you can then move on to the next step of the simulation. 

<img width="1917" height="1017" alt="A3_External_Forces" src="https://github.com/user-attachments/assets/4b3dbe73-edf3-4976-9565-b9f122107104" />

In this step of the simulation, you can apply external forces, torques, pressure, gravity, and temperature to the object in the simulation. For this project we were required to apply a force between 300lbf - 500lbf, in which I chose 400lbf to the outside of the aluminum bar to represent load force. 

<img width="1917" height="1017" alt="A3_FEA_Diagram" src="https://github.com/user-attachments/assets/910980d3-2c5f-4fe3-a118-da718de2e24e" />

Once you have selected the fixture and the external forces, you can then move onto meshing your object and running the simulation. This will give you the FEA Diagram that shows what happens to the object when the loaded force is applied to the object. When running this simulation, you can see where deformation occurs and where it is most stressed on the aluminum bar. 

<img width="3500" height="1095" alt="IMG_7827" src="https://github.com/user-attachments/assets/d108d93d-89d7-4e80-b4cd-3afe507f83f4" />

The max stress from the FEA Diagram is shown to be 2.26711ksi, the strength of aluminum is given as 40ksi. With this information, the safety factor was calculated to be 17.644. 


## Design Reflection:

<img width="3500" height="1034" alt="IMG_7829" src="https://github.com/user-attachments/assets/4481c329-507d-42b3-9b1c-2f8b70d4ce04" />

After making these calculations, there could be some issues with the material properties that is makes it have a high percent error. There could also be other factors that can't be determined but with this information, it shows that the slightest miscalculation can cause a big change is displacement. With these results, I would like to check  back with the simulation and ensure that the values shown are accurate but I would also like to double check my hand calculations to ensure that they are along the same range. One of the biggest differences that I seen from the values that I was given or calculated was the material property. This could be the cause of why there is a huge difference in displacement as well. 

# Pin Hole:
(5%) Now imagine a fairly substantial pin hole on the left side of the bar. Look up the stress concentration factor (Kt) for a hole in a flat bar in tension (Peterson's charts or Machinery's Handbook). Using your FEA's nominal stress away from the hole, estimate the peak stress at the hole and state whether it would still pass your safety factor. (Don’t redo the FEA!)

(5%) Lessons Learned document mistakes made and actual time spent from start to finish.

## Topic: Modify Design Parameters

Cycle through #2, change each of the design parameters which include load, thickness, height and width. Keep the material and the fixture the same. Before you calculate, take a guess if the length will increase, decrease, or stay the same. (You will not be penalized for guessing incorrectly.)

