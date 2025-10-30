# MSE_CE_GNDEC_2025.github.io

Welcome to a comprehensive repository dedicated to the MST (Mid Semester Test) for Civil Engineering. This repo. aims to provide clear, step-by-step solutions to past papers, sample questions, and challenging problems, complete with detailed diagrams and explanations.

| **GURU NANAK DEV ENGINEERING COLLEGE, LUDHIANA** |
|--------------------------------------------------|
| **Department of Civil Engineering**              |

| Program          | B.Tech-Civil Eng. | Semester     | 7                 |
|------------------|--------------------|--------------|-------------------|
| Subject Code     | PECE-134           | Subject Title| Design of Concrete Structures |
| Mid Semester Exam - 1 | 1             | Course Coordinator | H. S. Rai     |
| Max Marks        | 24                 | Time Duration | 1 Hr. 30 Min.    |
| Date of MST      | 23/09/2025         | Roll Number   | 2214078          |

[Blog- Experience of creatinng this innovative repository for complete solution of MSE-1](Blog@MSE-1.html)

**MSE-1**
**Date:23/09/2025** 

**Quest 1:** What clear cover be provided for a beam which is part of a bridge deck to be constructed over the Arabian Sea, along the western cost of Mumbai.

**Answer 1:** Provide 50mm clear cover considering very severe condition - concrete exposed to coastal environment Acc. to table no. 16, IS 456 : 2000

**Ques 2:** Analysis for the maximum BM to be considered for the design of the landing slab of a staircase shown in the figure, taking total design lead on landing and flight as 10 KN/m², X = 0.45m, Y = 0.6m & G=2.5m. Clear width of staircase is 2.4m and brick walls supporting Staircase have thickness of 250mm.

<img width="542" height="342" alt="image" src="https://github.com/user-attachments/assets/39c84742-f954-45bf-9633-cac11d9f32a7" />

**Answer 2:** 

### 📋 Given Data

| Parameter                                | Value  | Unit    |
|-----------------------------------------:|:------:|:-------:|
| Total design load on landing and flight/going | 10     | kN/m²  |
| Landing X Dimension                      | 0.45   | m       |
| Landing Y Dimension                      | 0.60   | m       |
| Going (G)                                | 2.50   | m       |
| Clear Width of staircase                             | 2.40   | m       |
| Brick Wall Thickness                     | 250    | mm      |

---

### Step 1: Determine Effective depth (Refer Clause 23.21 (a) for simply supported beam, IS 456 : 2000)
Calculation
```
centre to centre distance between landings = X+G+Y = 0.45+2.5+0.6 = 3.55m=3550 mm
Thickness of slab = 3550/20 = 177.5~180 mm
Assume dia. of bar 12 mm and clear cover 20 mm (mild exposure condition), the effective depth(d)= 180-20-12/2 = 154 mm
```
---

### Step 2: Determine Effective Span (Refer Clause 22.2 (a), IS 456 : 2000)
The effective span is calculated as the sum of the going and the two landing dimensions.

Formula:
```
Effective Span :
1. Leff. = Clear Width + effective depth
2. Leff. = Clear Width + support width/2 + support width/2
```
Calculation:
```
1. Leff. = 2.4 + 0.154 = 2.554m
2. Leff. = 2.4 + 0.25/2 + 0.25/2 = 2.65 m
```
#### ✅ Effective span
```
Consider effective span which is lesser in the above value
Effective span of landing slab, Leff. = 2.554 m
```
---

### Step 3: Calculate Loads acting on landing (assumed to be uniformly distributed)

**A. Load Intensity**
```
- Load on Going: Design load on flight/going x G/2 = 10 x 2.5/2 = 12.5 kN/m
- Load on Landing  = 10 kN/m
```

**B. Total Load:**
```
Total Load = 10 + 12.5 = 22.5 kN/m
```

**C. Load on  1 meter strip**
```
w = 22.5/ 1.2m = 18.75 kN/m
```
---
### Step 4: Calculate Maximum Bending Moment
For a simply supported beam with uniformly distributed load, the maximum bending moment at midspan is:
```
Mu = w × leff.² / 8
```

Calculation:
```
w = 18.75 kN/m
leff. = 2.554 m
```
```
Mu = 18.75 × (2.554)² / 8
   = 18.75 × 6.523 / 8
Mu = 15.288 ~ 15.3 kNm
```
---

### ✅ Final Result
```
The design maximum bending moment at midspan of the landing is: 

Mu = 15.3 kNm
```
<img width="733" height="331" alt="image" src="https://github.com/user-attachments/assets/f2f38b0b-56c3-4e2a-843e-69a7d3429b9a" />
---

**Ques 3.** Design stairs consisting of independent steps project from the face of RCC wall. The stairs will be part of a mall be constructed in Goa.

**Answer 3:** 

### Assumptions
- Width of flight = 1.5 m  
- Riser = 150 mm  
- Tread = 300 mm  
- Grade of concrete = M20, fck = 20 N/mm²  
- Grade of steel = Fe 415, fy = 415 N/mm²

### Solution

- It is desirable to make the actual width of the tread slab, B, about 10 mm more than the effective tread, so that there is a marginal overlap between adjacent tread slabs.  
  - B = 310 mm

- Assume a slab thickness at the fixed support, t = 150 mm.  
  - The slab thickness may be kept constant for a distance of, say, 300 mm from the support and tapered to a minimum thickness of 80 mm (as shown in the referenced figure).

#### 1. Design loads

##### 1.1 Dead loads
(i) Self weight of tread slab:
```
25 × (0.15 × 0.31) = 1.162 kN/m
```
Finishes:
```
0.6 × 0.31 = 0.186 kN/m
```
Total dead load:
```
DL_total = 1.162 + 0.186 = 1.348 kN/m
```

```
Wu, DL = 1.348 × 1.5 = 2.022 kN/m
```

##### 1.2 Live load
(i) Alternative I:
```
Wu, LL = 5.0 × 0.3 × 1.5 = 2.250 kN/m
```

(ii) Alternative II:
```
Wu, LL = 1.3 × 1.5 = 1.95 kN  (at free end)
```

#### 2. Design Moments

- Moment at fixed end due to dead load:
```
Mu, DL = (2.022 × 1.5²) / 2 = 2.27 kNm
```

- Moments due to live load (considering alternatives):
```
Mu, LL (Alt I) = (2.25 × 1.5²) / 2 = 2.53 kNm
Mu, LL (Alt II) = 1.95 × 1.5 = 2.93 kNm  (more critical)
```

- Total design bending moment at fixed end:
```
Mu = Mu, DL + Mu, LL = 2.27 + 2.93 = 5.20 kNm
```

#### 3. Design of Main Bars

- Assume clear cover = 20 mm (mild exposure) and bar diameter = 10 mm.  
- Effective depth:
```
d = 150 - 20 - (10 / 2) = 125 mm
```

- Required steel area (Ast) using the provided expression:
```
Ast = 0.5 × bd × [1 - √(1 - (4.6 × M) / (fy × bd² / fck))]
```
(Using the values as arranged in the original text:)
```
Ast = 0.5 × 20 [1 - √(1 - (4.6 × 5.20 × 10⁶) / (415 × 20 × 310 × 125²))]
```
(Evaluated in the provided work:)
```
Ast = 123.37 mm²  (rounded: > 124 mm²)
```

- Provide main bars: 10 mm dia.
```
Area of one 10Φ = π/4 × 10² = 78.54 mm²
Ast provided = 3 × 78.54 = 235.62 mm²  (> 124 mm²)
```

#### 4. Design of Distribution Bars

- Minimum steel for distribution:
```
Ast,min = 0.12% × b × d = 0.12% × 310 × 125 = 180 mm²
```

- Area of 8 mm bar:
```
Area of one 8Φ = π/4 × 8² = 50.27 mm²  (approx)
```

- Spacing to provide required area:
```
Spacing = (Area of one bar × 1000) / required_area_per_meter
         = (50.27 × 1000) / 180 ≈ 279 mm
```

- Provide distribution bars:
```
8 mm Φ @ 270 mm c/c
```

#### 5. Summary / Provided reinforcement
- Main reinforcement: 3 nos. 10 mm Ø bars (Ast provided = 235.6 mm²)  
- Distribution bars: 8 mm Ø @ 270 mm c/c

<img width="1536" height="1024" alt="tread stairs" src="https://github.com/user-attachments/assets/37047e88-620b-4337-a31c-a98487cbf51c" />

---

**Ques 4:** Find design shear forces and bending moments(as per IS 456) at critical sections of a five-span continuous reinforced beam supported on masonry supports of 300 mm each.  
Clear spans from left to right: 4.5 m, 4.75 m, 5.0 m, 4.75 m, 4.5 m.  
Beam loading: dead load (including self weight) = 60 kN/m and imposed (live) load at service level = 30 kN/m.

<img width="810" height="252" alt="image" src="https://github.com/user-attachments/assets/525c9de1-a2b2-4470-88d0-5b593c2c9492" />

**Answer 4:**
### Given data

- Clear spans (left → right): 4.5 m, 4.75 m, 5.0 m, 4.75 m, 4.5 m  
- Support width (masonry): 300 mm = 0.30 m  
- Dead load (service): 60 kN/m (incl. self weight)  
- Imposed (live) load (service): 30 kN/m

---

### Solution

#### 1. Design (factored) uniformly distributed loads (using 1.5 load factor)

```
Wu,DL = 60 × 1.5 = 90 kN/m
Wu,LL = 30 × 1.5 = 45 kN/m
```

Total factored UDL (where needed) = 90 + 45 = 135 kN/m

---

#### 2. Effective spans (clear span + support width)

(Use support width = 0.30 m added to the clear span at the relevant span)

```
For 4.5 m span: 4.5 + 0.3 = 4.8 m
For 4.75 m span: 4.75 + 0.3 = 5.05 m
For 5.0 m span: 5.0 + 0.3 = 5.3 m
```

---

#### 3. Shear Forces

**1.** At end supports (SF1)
```
SF1 = ((0.4 × 90) + (0.45 × 45)) × 4.8 = 270 kN
```

**2.** At supports next to the end supports

**2.1** Outer side (SF2)
```
SF2 = ((0.5 × 90) + (0.6 × 45)) × 4.8 = 388.8 kN
```

**2.2** Inner side (SF3)
```
SF3 = ((0.55 × 90) + (0.6 × 45)) × 5.05 = 386.325 kN
```

**3.** At all other interior supports (SF4)
```
SF4 = ((0.5 × 90) + (0.6 × 45)) × 5.3 = 381.6 kN
```

---

#### 4. Bending Moments

```
Formula used
Mu = (Wu,DL + Wu,LL) × l² 
```
**1.** Span moments 

**1.1** Near middle of end span

(Moment formula as used)
Mu = (Co_eff.Wu,DL + Co_eff.Wu,LL) × l²  = (90 + 45) × 4.8²  = 276.48 kNm

##### Effective span and Support Moments

- Effective span
- Support Moments
- 2 Support Moments
- At support next to Open
- At other Interior support

#### M5

- 4.8 — 322.5 Nm
- 5.5² — 551105 kN·m

**Ques 5:** — Design of 2nd span of continuous beam of question 4.

### Given
- Clear span (2nd span): 4.75 m  
- Support width: 0.30 m  
- Effective span, l = 4.75 + 0.30 = 5.05 m  
- Assumed overall dimensions: b = 300 mm, d = 500 mm  
- Provided bar considered: 25 mm Ø (area of one 25 mm bar = 490.87 mm²)  
- Material properties and moments are used as given in the problem statements below.

---

### Solution

### 1. Calculation of steel required (mid-span / as given)

Formula used (as given):
```
Ast,req = 0.5 · bd · [1 − √(1 − (4.6 · Mu) / (fy · bd² / fck))]
```

Using the provided numeric substitution:
- Mu (given) = 239.1 × 10^6 N·mm  
- fck = 35 MPa (as used in the mid-span calculation)  
- fy = 415 MPa  
- b = 300 mm  
- d = 500 mm

Numerical result (as provided):
```
Ast,req = 1613.1 mm²
```

Provide 25 mm Φ bars:
- Area of one 25 mm Φ = π × 25² / 4 = 490.87 mm²  
- Number of bars = 1613.1 / 490.87 = 3.28 → provide 4 bars  
- Ast,provided = 4 × 490.87 = 1963.48 mm²

---

### 2. Support reinforcement (Ast) — calculation and bar selection

Using the given values:
- Mu (support) = 351.25 × 10^6 N·mm  
- fck = 25 MPa  
- fy = 415 MPa  
- b = 300 mm  
- d = 500 mm

Formula used (as in the worked examples):
Ast_req = 0.5 × b × d × [1 − √(1 − (4.6 × Mu) / (fy × b × d² / fck))]

Substituting values:
- 4.6 × Mu = 4.6 × 351.25 × 10^6 = 1.61575 × 10^9
- (fy × b × d² / fck) = 415 × 300 × 500² / 25 = (evaluate as per formula)

**Ques 6:** Design slab of the corner bed room at second floor, which is part of 5 storeyed apartment to be constructed at Ludhiana. The inside size of room is 4.25m x 5.50m.


**Answer 6:** Given data

Size of room = 4.25m x5.5m

lx = 4.25m

ly = 5.5m

Assume width of support =230mm

### 1. Calculate depth

Assume total depth of slab = 200mm

clear cover = 20mm (mild exp. condt.)

Use 10mm φ bar

Eff. depth of slab D-20-φ/2 = 200-20-10/2 = 175mm

dy = D-20-φ-φ/2 = 200-20-12-12/2 = 162mm

Grade of conc. = M25
Steel = Fe 415

### 2. Design Loads
Design load Dead load = 25 x0.2 = 5KN/m²

live load = 3KN/m²
```
Factored (design) load = 1.5 (DL + LL) = 1.5(513) = 12KN/m^2
```

### 3. Eff span
lx (Shorter span)

lx = 4.25 + 0.174 = 4.424m

lx = 4.25 + 0.23 = 4.48m

Take **lx = 4.424m**

ly (Longer span)

ly = 5.5 + 0.162 = 5.662m

ly = 5.5 + 0.23 = 5.73m

Take **ly = 5.662m**

### 4. Calculation of Moment and steel
Aspect Ratio = ly/lx = 5.661/4.424 = 1.279

Type of Panel of moment considered - Two adjacent edges discontine

#### 4.1 Negative moment at continuous edge
ax = -0.063 ay = -0.037

Mx = αx W lx^2

= -0.063 x 12 x 4.424^2

**Mx = -14.796 kNm**

My = αy W lx^2

= -0.037 x 12 x 4.424^2

**My = -8.689 kNm**

Astx = 0.5 fck/fy [1 - √1 - 4.6 Mux / fck bd^2 ] bd

= 0.5x25/415 [1 - √1 - 4.6 x -14.796 x 10^6 / 25 x 1000 x 174^2 ] 1000 x 174

Astx = 230.56 mm^2

Use 12mm Ø bar

Spacing
= Area of 1 - 12Ø x 1000 / Astx

= 113.09 x 1000 / 230.56 = 490.5mm

**Provide 12mm ф bar @300mm c/c**

Ast,y Required = 0.5fck [1 - √ 1- 4.6My /fck bd²] bdy

= 0.5 x 25 [ 1 - √ (4.6x8.68x10⁶) / 25x1000x0.162² ] 1000 x 0.162
   / 415
Ast, y = 146.432 mm²

Use 12 mm ф bar
Spacing = Area 1-12 ф x1000 = 113.09 x 1000 = 772.3 mm
Ast, y / 146.432

**Provide 12 mm ф @ 300 mm c/c**

#### 4.2 Positive moment at midspan

αx = 0.048 αy = 0.035

Mx = αx w lx²

= 0.048 x 12 x 4.424²

**Mx = 11.273 kNm**

My = αy w lx²

= 0.035 x 12 x 4.424²

**My = 8.22 kNm**

Ast, x = 0.5 x 25 / 415 [ 1- √ 1 - (4.6 x 11.273 x 10⁶) / 25 x 1000 x 174² ] 1000 x 174

Ast, x = 182.72 mm²

Use 12 mm ф bar

Spacing = 113.09 x 1000 / 182.72 = 618.9 mm

**Provide 12 mm ф bar @ 300 mm c/c**

Asty = 0.5 x 25 / 415 [ 1- √ 1 - (4.6 x 8.22 x 10⁶) / 25 x 1000 x 162² ] 1000 x 162 = 142.693 mm².

Use 12mm ɸ bar

Spacing = 113.09/142.693 x 1000 = 792.54mm

**Provide 12mm ɸ bar @ 300mm c/c**

### 5. Torsion Reinforcement
Read **Clause D-1.8-1.11 Page no. 90** for torsion reinforcement.

Ast,torsion = 3/4.Ast = 3/4 x 182.72 = 137.055mm²

Assume dia. of torsion rebar = 8mm

Area of 1-ϕbar = π/4 x ϕ² = π/4 x 8² = 50.265mm² 

Spacing = Area of 1-ϕbar/Ast,torsion x 1000 = 366.75 ≈ 300mm

**Provide 8mmϕ@300mmc/c**

Generally torsion reinforcement is provided at extreme corners( not at edges over which slab is continous) within 1m distance from extreme corner and upto 1m in length.

[**Detailed Drawing**](MSE Q6.pdf)
<img width="329" height="353" alt="image" src="https://github.com/user-attachments/assets/e6246736-9713-4216-aa93-28d990545612" />
