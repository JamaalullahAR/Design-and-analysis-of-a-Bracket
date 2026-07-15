# Design and analysis of a Bracket

## Overview
This project required us to design and manufacture a bracket using FEA. While working in pairs, we had to undertake a funnel design process to narrow our initial ideas and decide as a team which concept to move forward with. After finalising our concept, we had to generate a G-code for manufacturing and physically test our component to check if our FEA analysis lined up with real world testing, and whether our concept was acceptable for further production. 

## Objectives
- The component needed to have a resisting force of 3kN from an upward displacement of 1mm.
- The component needed to have a resiting force of 4kN from a downward displacment of 1mm.
- Needs to have 2 zones clear for pipes and wires.

## Tools and concepts used
- Inventor
- ANSYS FEA
- Mesh convergence
- Validation of results from real experimental values from a 2016 model
- Buckling caclculations

## Methodology
- Each of us decided come up with multiple concepts, and test them in ANSYS with simple boundary conditions. Whichever concept yielded the best result would be selected to push forward for the team discussion. The closest concept to the specification was pushed forward for the design used for the FEA setup.
- We decided as a team that it was better for the part to be overstiff, rather than understiff. Thus we went for a more conservative design.
- A 2016 model was then used, and different boundary conditions implemented, and different Young's modulus values used to get the most accurate set up to use on our final FEA model.
- After yielding a final FEA setup, the set up was used on our final design. The model was re designed and modifed to get resisting forces to as close to the required forces.
- A mesh convergence study of Von Mises stress was done to check if our results were reaching a certain value.
- After all FEA analysis was done, and our final component design was selected, a G-Code was made using Inventor.
- It was sent for manufacturing and tested at the Newmarket campus of UOA.
- Simple buckling calculations were done for the report for checking if the bracket would undergo buckling.

## Results 
- Our component managed to pass both the compressive and tensile stresses.
- It had a reaction force of 3366N from the upwards displacement of 1mm.
- It had a reaction force of 4181N from the downwards displacement of 1mm.
- It was overstiff in both upwards and downwards displacements.
- When tested up to 10kN of compressive force, the component had a reaction force of 5922N, and it yielded slightly in the displacement hole.
- Overall, the component yielded a close result to our expected FEA model, and managed to survive the testing.
- However, the component could be optimised for lesser mass, and get a closer value to the required forces.

## Project images

## What I learnt
- How to work as a team when it comes to FEA.
- Getting better at using ANSYS and how different boundary systems affects the output of the model.
- Learnt how to use ANSYS software like DesignModeller to add/remove parts of the imported STEP file.
- I realised that I could have done more to help my partner, as we went forward with her part. I could have expereimented or taken responsibilty for the G-code generation. However, what I did was begin the report and try to catch up with the FEA modelling.
- I also realised how important a proper computer was for doing FEA modellling. My computer kept crashing or yielded bad results, which ultimately led me to contributing less. So I had to make sure that I used a stronger computer for any kind of modelling in the future.

<!-- <p align="center">
  <img src="" width="800">
</p>

<p align="center">
  <i>Figure 1: </i>
</p> --!>


