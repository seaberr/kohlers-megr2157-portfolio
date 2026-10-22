![MEGR 2156-7 Title](MEES_Logo_Standard.png)
# A7 – FEA on Bracket
My Bracket has 1023 carbon steel applied to it.
## Outer Loop: Based on Design Optimization

Judging by the assignment detail it appears this will be an iterative design process where we try multiple things and then check and modify to receive our desired result
## Inner Loop: Based on validation

## Preprocessing
## Design Optimization
Review results to make geometric changes, adding and removing material where needed in an attempt to modify the component to be stronger, stiffer, and more lightweight than the prior solutions.
Repeat #1 through #3  a minimum of three times.

### Hangar Attempt 1
#### Perform a static stress analysis
![MEGR 2156-7 Title](IMG_6897.JPEG)
#### Select a mesh 
I chose the Finest mesh Because the Finest Mech is the most likely to be 
![MEGR 2156-7 Title](IMG_6898.JPEG)
![MEGR 2156-7 Title](IMG_6901.JPEG)
### Hangar Attempt 2 
Our updated design incorrperates a latteral support to counter act the moment arm created by the long overhang of the cylindrical beam.
![MEGR 2156-7 Title](IMG_6903.JPEG)
![MEGR 2156-7 Title](IMG_6905.JPEG)
### Hangar Attempt 3
The third iteration receives an update on the removal of 90-degree corners where there are stress concentrations
![MEGR 2156-7 Title](IMG_6907.JPEG)
![MEGR 2156-7 Title](IMG_6908.JPEG)
![MEGR 2156-7 Title](IMG_6909.JPEG)
![MEGR 2156-7 Title](IMG_6912.JPEG)
![MEGR 2156-7 Title](IMG_6914.JPEG)
### Link Attempt 1
![MEGR 2156-7 Title](IMG_6919.JPEG)
![MEGR 2156-7 Title](IMG_6921.JPEG)
 ### Link Attempt 2
 The second iteration attempts to hold the wall away from deflection by adding more material and strength with it's extruded triangle feature.
![MEGR 2156-7 Title](IMG_6923.JPEG)
![MEGR 2156-7 Title](IMG_6927.JPEG)
 ### Link Attempt 3
 The added support I supposed to reduce the strain that is in the vertical direction I added more material on the sides and the bottom hoping it will brace the body from strain so it doesn't look like our last one.
![MEGR 2156-7 Title](IMG_6931.JPEG)
![MEGR 2156-7 Title](IMG_6932.JPEG)
#### Computation Solve
We can do this like we did in the last assignments if necessary
#### Data Interpretation
Interpreting the data is how we understand what we are looking at. If you need help watch a YouTube video
#### Review the results by tabulating the safety factor
yield stress/Max stress 
#### maximum stress and it’s location
The max stresses are able to be sean in Blue on each one of these pictures there is also a bar to the side of some of these FEA analysis which allows anyone to understand where the part is under stress.
#### maximum displacement and it’s location  
The max displacement is at the very tip of the hangar and the bottom of the Link
#### Error Estimation
I tried to reduce error by a lot when I made the mesh as fine as possible Your calculations will be better if you do this because the number will be way closer to the actually because the is how approximations and calculus work.

## Reflections
The biggest realization I came into was the reality that I had to use the school's computers in the mosaic lab If I wanted to use the simulation functions in SolidWorks. This wasted a lot of my time because no one told me that, The assignment said that Creo would not work at home but it did not tell me about SolidWorks. The secound thing I learned was things dont always load the way you exspect. I designed for a specific load but I had weak points which made my capabilities a lot more limited.
2157 Students Only (30%)
Topic: Finite Element Method
Complete the same process above for the link.

Resources:
Solidworks
SOLIDWORKS FEA Static Simulation in 10 Mins ! - TforDesign

