![MEGR 2156-7 Title](MEES_Logo_Standard.png)
# A3 – Parametric and FEA
### Instructions:
This week you have the opportunity to design for stiffness by producing/designing a bar using two types of analysis: axial deflection in the form of parametric modeling and finite element analysis. This assignment will enhance your comprehension of relating different parameters with each other, which include loads (forces), geometry (length/area) and materials. Remember, showcase your work in your portfolio/virtual notebook linking CAD files, sketches, drawing, calculations, writings etc. Submit a pdf through canvas. Make sure your portfolio/virtual notebook is structured and readable to your audience.

If applicable, scan your written work and embed (not upload) them in your assignment page in your portfolio.
### Documentation:
The documentation’s intent is to capture your work and learning process from the time you read through the assignment all the way until you turn in your work. Your work may include but not limited to your thoughts, your insights, your mistakes, your drawings, your calculations etc. A thorough example of documentation can be found on Carlos Soriano’s e-portfolio HERE. Notice how he captured his learning by noting the differences in the Modulus of Elasticity for each analysis.

Document each step in the process, no step is too small.
Document the process which includes many pictures with overviews of images
Detailed lessons learned throughout the process
Detail any mistakes throughout the process
Actual time it took from start to finish
Failure to put a link for downloading your CAD file will result in a 15% deduction to your final grade.

Failure to input headers in your assignment will result in a 15% deduction to your final grade.

### Objectives:
Use axial deflection modeling to design its dimensions
Use parametric design to determine a bars length
Introduce you to FEA (Finite Element Analysis)
Introduce you to linking dimensions to appropriate parameters in CAD.
Compare and contrast the different analysis
### Reading:
Machinery’s Handbook:
Deflections 218
“Why Engineers Design with Parametric 3D” - AutoDesk
### Description:
You are to design a bar which has a circular cross section where the values of the criteria given for the material, maximum deflection, and load. Determine the bar’s minimum geometry (ie.. length, diameter, and weight) through parametric design while under direct tension. Then verify the geometry through finite element analysis.
### utline:
(45%) Parametrically design a bar in CAD with an applied direct load between 300 lbf < F < 500 lbf. The max axial deflection of the bar is .009 inches. The bar is to be designed from Aluminum with a range of Young’s Modulus from (8.5 - 11.5) x 106 psi.
(5%) Choose the values for the cross sectional area of the bar. (width, height, and thickness)
(5%) Use the direct tension elongation equation in the Machinery’s Handbook to parametrically determine the length of the bar.
(35%) Generate the bar in CAD by assigning the parameters of Modulus of Elasticity, max deflection, load, width, height, and thickness to parametric equations in order to determine the length of the bar.
(40%) Conduct a FEA on the bar using the same load used to generate the bar's geometry.
(20%) Generate a deflection map in the FEA.
(20%) Generate a von Mises Stress map.
(5%) Check the maximum stress is lower than the strength of Aluminum (Sy = 40 ksi) and note the safety factor.
(10%) Design Reflection
(5%) Report the axial deflection from your parametric hand-calculation and from your FEA. Calculate the percent difference between the two.
If there is a meaningful discrepancy, identify at least one likely source (e.g., assumptions in the hand-calc, boundary conditions, mesh density, material property inputs).
If the two values are essentially the same, explain why you'd expect them to agree for this geometry and loading (e.g., no stress concentrations, simple axial loading, coarse mesh still adequate for a uniform cross-section).
Either way, state which result you'd trust more for this design and why.
(5%) Now imagine a fairly substantial pin hole on the left side of the bar. Look up the stress concentration factor (Kt) for a hole in a flat bar in tension (Peterson's charts or Machinery's Handbook). Using your FEA's nominal stress away from the hole, estimate the peak stress at the hole and state whether it would still pass your safety factor. (Don’t redo the FEA!)
(5%) Lessons Learned document mistakes made and actual time spent from start to finish.
### 2157 Students Only
(20%) Topic: Modify Design Parameters

Instructions:

Cycle through #2, change each of the design parameters which include load, thickness, height and width. Keep the material and the fixture the same.

Before you calculate, take a guess if the length will increase, decrease, or stay the same. (You will not be penalized for guessing incorrectly.)

Resources:
Video of parametric design in Fusion 360 HERE
Video of FEA in Fusion 360 HERE
Video for FEA in Creo  HERE
Video for how to choose a material in Creo HERE
Video of parametric design in Solidworks HERE
FEA video in Solidworks HERE
Matweb Material Property Data HERE
# Parametric Bar Design and Finite Element Analysis

## Assignment Overview

### Objectives

- [ ] Use axial deflection calculations to design the dimensions of a bar.
- [ ] Use parametric CAD design to determine the bar length.
- [ ] Perform a Finite Element Analysis (FEA).
- [ ] Link CAD dimensions to engineering parameters.
- [ ] Compare hand calculations with FEA results.
- [ ] Evaluate the safety factor of the design.
- [ ] Document the entire design process, including mistakes and lessons learned.

---

# 1. Initial Design Requirements

## Design Requirements

The bar must satisfy the following requirements:

- Material: Aluminum
- Applied axial load: between **300 lbf and 500 lbf**
- Maximum allowable axial deflection: **0.009 in**
- Young's Modulus range: **8.5 × 10^6 psi to 11.5 × 10^6 psi**
- Aluminum yield strength used for safety-factor calculation: **40 ksi**

### My Selected Design Parameters

| Parameter | Value | Units |
|---|---:|---|
| Applied Load, F | _____ | lbf |
| Young's Modulus, E | _____ | psi |
| Maximum Deflection, δ | 0.009 | in |
| Width / Diameter | _____ | in |
| Height | _____ | in |
| Thickness | _____ | in |
| Cross-Sectional Area, A | _____ | in² |
| Calculated Length, L | _____ | in |

---

## Why I Chose These Values

Answer:

- Why did I choose this load?
- Why did I choose these cross-sectional dimensions?
- Why did I choose this value of Young's Modulus?
- Is the Young's Modulus within the required aluminum range?
- Are the dimensions practical to manufacture/model?

**Response:**

[Write response here]

---

## Design Sketch

Add a hand sketch or CAD sketch showing:

- [ ] Bar geometry
- [ ] Cross-sectional dimensions
- [ ] Length
- [ ] Fixed end
- [ ] Applied load
- [ ] Direction of load

### Image

![Initial Design Sketch](IMAGE-LINK-HERE)

**Figure 1.** Initial sketch of the bar showing dimensions, fixture, and axial load.

---

# 2. Axial Deflection Hand Calculation

## Governing Equation

For a uniform bar under direct axial tension:

\[
\delta = \frac{FL}{AE}
\]

Where:

- \( \delta \) = axial deflection
- \( F \) = applied axial force
- \( L \) = bar length
- \( A \) = cross-sectional area
- \( E \) = Young's Modulus

Solving for the required length:

\[
L = \frac{\delta AE}{F}
\]

---

## Cross-Sectional Area Calculation

### If using a circular bar:

\[
A = \frac{\pi d^2}{4}
\]

### If using a rectangular bar:

\[
A = wt
\]

Use the equation corresponding to the geometry actually used in the CAD model.

### Calculation

\[
A =
\]

Show all work here:

[Insert calculation]

---

## Length Calculation

Known values:

\[
F =
\]

\[
E =
\]

\[
A =
\]

\[
\delta = 0.009\text{ in}
\]

Substitute into:

\[
L = \frac{\delta AE}{F}
\]

### Calculated Length

\[
\boxed{L = \_\_\_\_\_ \text{ in}}
\]

---

## Hand Calculation Image

Add a clear photograph or scan of the complete hand calculation.

![Axial Deflection Hand Calculation](IMAGE-LINK-HERE)

**Figure 2.** Hand calculation used to parametrically determine the bar length.

---

# 3. Parametric CAD Model

## CAD Program Used

Software:

**[Creo / SolidWorks / Fusion 360]**

---

## Parameters Created

Create parameters for the required design variables.

- [ ] Young's Modulus
- [ ] Maximum deflection
- [ ] Applied load
- [ ] Width or diameter
- [ ] Height
- [ ] Thickness
- [ ] Cross-sectional area
- [ ] Length

### Parameter Table

| CAD Parameter | Value | Units |
|---|---:|---|
| LOAD | _____ | lbf |
| MODULUS | _____ | psi |
| DEFLECTION | 0.009 | in |
| WIDTH / DIAMETER | _____ | in |
| HEIGHT | _____ | in |
| THICKNESS | _____ | in |
| AREA | _____ | in² |
| LENGTH | _____ | in |

---

## Parametric Equation

The length of the bar was controlled using:

\[
L = \frac{\delta AE}{F}
\]

### CAD Equation Used

```text
[Paste the exact parameter/equation syntax used in your CAD program here]

