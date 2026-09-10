![MEGR 2156-7 Title](MEES_Logo_Standard.png)
# A3 – Parametric and FEA



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

Software: CREO
[Download Project Report](a3terror.prt.1)
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

