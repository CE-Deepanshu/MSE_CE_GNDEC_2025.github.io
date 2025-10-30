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

**[Answer 1:](index1.md)** 

---

**Ques 2:** Analysis for the maximum BM to be considered for the design of the landing slab of a staircase shown in the figure, taking total design lead on landing and flight as 10 KN/m², X = 0.45m, Y = 0.6m & G=2.5m. Clear width of staircase is 2.4m and brick walls supporting Staircase have thickness of 250mm.

<img width="542" height="342" alt="image" src="https://github.com/user-attachments/assets/39c84742-f954-45bf-9633-cac11d9f32a7" />

**Answer 2:** 

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
(1) Self weight of tread slab = 25 × (0.15 × 0.31) = 1.162 kN/m

(2) Finishes = 0.6 × 0.31 = 0.186 kN/m

Total dead load, DL = 1.162 + 0.186 = 1.348 kN/m

$$Wu_{DL}$$ = 1.348 × 1.5 = 2.022 kN/m


##### 1.2 Live load
(i) Alternative I:

$$Wu_{LL}$$ = 5.0 × 0.3 × 1.5 = 2.250 kN/m

(ii) Alternative II:

$$Wu_{LL}$$ = 1.3 × 1.5 = 1.95 kN/m (at free end)

#### 2. Design Moments

- Moment at fixed end due to dead load:

$$Mu_{DL} = \frac{(2.022 × 1.5²)}{2}$$ = 2.27 kNm

- Moments due to live load (considering alternatives):

$$Mu_{LL} (Alt I) = \frac{(2.25 × 1.5²)}{2}$$ = 2.53 kNm

$$Mu_{LL}$$ (Alt II) = 1.95 × 1.5 = 2.93 kNm  (more critical)
  
-Total design bending moment at fixed end:

Mu = $$Mu_{DL} + Mu_{LL}$$ = 2.27 + 2.93 = 5.20 kNm


#### 3. Design of Main Bars

Assume clear cover = 20 mm **(mild exposure)** and bar diameter = 10 mm.  
**Effective depth:**

d = 150 - 20 - $$\frac{10}{2}$$ = 125 mm

**Required main steel area (Ast) using the following expression:**

$Ast_{req} = \frac{0.5·f_{ck}}{f_y}·[1 − √\frac{1 − (4.6 · Mu)}{f_ck·bd²}].bd$

 = $$\frac{0.5·20}{415}·[1 − √\frac{1 − (4.6 · 5.2 x 10^6)}{20·310.125²}].310.125$$

$$Ast_{req}$$= 123.37 mm² ~ 124 mm²

Provide main bars of 10 mm dia.

Area of one 10Φ = $$\frac{π}{4}$$ × 10² = 78.54 mm²

No. of bars = $$\frac{Ast_{req}}{Area of one 10Φ} = \frac{124}{78.54}$$ = 3 No.

$$A_{st provided}$$ = 3 × 78.54 = 235.62 mm²  ~ 124 mm²

#### 4. Design of Distribution Bars

**Minimum steel for distribution bars:**

$$A_{st,min}$$ = 0.12% × b × d = 0.12% × 310 × 125 = 180 mm²

Provide 8 mm bar:

Area of one 8Φ = π/4 × 8² = 50.27 mm²  (approx)

**Spacing** = $$\frac{Area of one 8Φ}{A_{st,min}}$$ x 1000
            = $$\frac{50.27 mm²}{180}$$ x 1000  = 278.88 mm

**Provide distribution bars 8 mm Φ @ 270 mm c/c**

#### 5. Summary / Provided reinforcement
**Main reinforcement: 3 nos. 10 mm Ø bars (Ast provided = 235.6 mm²)**

**Distribution bars: 8 mm Ø @ 270 mm c/c**

<img width="1242" height="396" alt="image" src="https://github.com/user-attachments/assets/b23de724-5717-4adc-a532-906ba0718b40" />

---

**Ques 4:** Find design shear forces and bending moments(as per IS 456) at critical sections of a five-span continuous reinforced beam supported on masonry supports of 300 mm each.  
Clear spans from left to right: 4.5 m, 4.75 m, 5.0 m, 4.75 m, 4.5 m. Beam is subjected to dead load (including self weight) of 60 kN/m and imposed (live) load of 30 kN/m at service level.

<img width="810" height="252" alt="image" src="https://github.com/user-attachments/assets/525c9de1-a2b2-4470-88d0-5b593c2c9492" />

**Answer 4:**
### Given data

- Clear spans (left → right): 4.5 m, 4.75 m, 5.0 m, 4.75 m, 4.5 m  
- Support width (masonry): 300 mm = 0.30 m  
- Dead load (service): 60 kN/m (incl. self weight)  
- Imposed (live) load (service): 30 kN/m

### Solution

#### **1. Design (factored) uniformly distributed loads (using 1.5 load factor)**

$$Wu_{DL}$$ = 60 × 1.5 = 90 kN/m

$$Wu_{LL}$$ = 30 × 1.5 = 45 kN/m


Total factored UDL (where needed) = 90 + 45 = 135 kN/m

#### **2. Effective spans (clear span + support width)**

(Use support width = 0.30 m added to the clear span at the relevant span as we don't know about effective depth)

For 4.5 m span: 4.5 + 0.3 = 4.8 m
For 4.75 m span: 4.75 + 0.3 = 5.05 m
For 5.0 m span: 5.0 + 0.3 = 5.3 m

#### **3. Shear Forces**
**Use Formula**

SF = $$(Coeff.Wu_{DL} + Coeff.Wu_{LL}) x l$$

For Example : ((0.4 × Wu_DL) + (0.45 × Wu_LL)) × 4.8

**1. At end supports (SF1)**

SF1 = ((0.4 × 90) + (0.45 × 45)) × 4.8 = 270 kN

**2. At supports next to the end supports**

**2.1 Outer side (SF2)**

SF2 = ((0.5 × 90) + (0.6 × 45)) × 4.8 = 388.8 kN

**2.2 Inner side (SF3)**

SF3 = ((0.55 × 90) + (0.6 × 45)) × 5.05 = 386.325 kN

**3. At all other interior supports (SF4)**

SF4 = ((0.5 × 90) + (0.6 × 45)) × 5.3 = 381.6 kN

#### 4. Bending Moments
**Formula used**

Mu = $$(Coeff.Wu_{DL} + Wu_{LL}) × l^2$$ 

##### **1. Span moments** 

**1.1 Near middle of end span**

M1 = $$(\frac{Wu_{DL}}{12} + \frac{Wu_{LL}}{10}) × l^2$$  = $$(\frac{90}{12} + \frac{45}{10}) × 4.8^2$$ = 276.48 kNm

**1.2 At middle of interior span**

M2 = $$(\frac{Wu_{DL}}{16} + \frac{Wu_{LL}}{12}) × l^2$$  = $$(\frac{90}{16} + \frac{45}{12}) × 5.05^2$$ = 239.1 kNm

M3 = $$(\frac{Wu_{DL}}{16} + \frac{Wu_{LL}}{12}) × l^2$$  = $$(\frac{90}{16} + \frac{45}{12}) × 5.3^2$$ = 263.34 kNm

##### **1. Span moments** 

**At support next to the end supports**

M4 = $$- (\frac{Wu_{DL}}{10} + \frac{Wu_{LL}}{9}) × l^2$$  = $$- (\frac{90}{10} + \frac{45}{9}) × 4.8^2$$ = -322.56 kNm

**At support next to the end supports**

M5 = $$- (\frac{Wu_{DL}}{12} + \frac{Wu_{LL}}{9}) × l^2$$  = $$- (\frac{90}{12} + \frac{45}{9}) × 5.3^2$$ = -351.125 kNm

---

**Ques 5:** — Design of 2nd span of continuous beam of **question 4**.

### Given
- Clear span (2nd span): 4.75 m  
- Support width: 0.30 m  
- Effective span, l = 4.75 + 0.30 = 5.05 m  
- Assumed overall dimensions: b = 300 mm, d = 500 mm  
- Provided bar considered: 25 mm Ø (area of one 25 mm bar = 490.87 mm²)  
- Material properties and moments are used as given in the problem statements below.

### Solution

#### **1. Calculation of steel required at mid-span ( as given)**

Formula used (as given):

$$Ast_{req} = \frac{0.5·f_{ck}}{f_y}·[1 − √\frac{1 − (4.6 · Mu)}{f_{ck}·bd²}].bd$$

Using the provided numeric substitution:
- Mu (given) = 239.1 × 10^6 N·mm  
- fck = 35 MPa (as used in the mid-span calculation)  
- fy = 415 MPa  
- b = 300 mm  
- d = 500 mm

$$Ast_{req} = \frac{0.5·35}{415}·[1 − √\frac{1 − (4.6 · 239.1 × 10^6)}{35·300.500²}].300.500$$

$$Ast_{req}$$ = 1613.1 mm²

Provide 25 mm Φ bars:
- Area of one 25 mm Φ = π × 25² / 4 = 490.87 mm²  
- Number of bars = 1613.1 / 490.87 = 3.28 → provide 4 bars  
- $$Ast_{provided}$$ = 4 × 490.87 = 1963.48 mm²

#### **2. Support reinforcement $$(A_{st})$$ — calculation and bar selection**

Using the given values:
- Mu (support) = 351.25 × $$10^6$$ N·mm  
- fck = 25 MPa  
- fy = 415 MPa  
- b = 300 mm  
- d = 500 mm

Substituting values:

$$Ast_{req} = \frac{0.5·f_{ck}}{f_y}·[1 − √\frac{1 − (4.6 · Mu)}{f_{ck}·bd²}].bd$$

  $$= \frac{0.5·25}{415}·[1 − √\frac{1 − (4.6 · 351.25 × 10^6)}{415·300.500²}].300.500 = 1646.63 mm^2$$

$$Ast_{req} at support = 1646.63 mm^2$$

Provide 25 mm Φ bars:
- Area of one 25 mm Φ = π × 25² / 4 = 490.87 mm²  
- No. of bars = $$\frac{Ast_{req}}{Area of one 10Φ} = \frac{1646.63}{490.87}$$ = 4 No.

#### **3. Reinforcement Summary**

**Provide 4-25 mm Φ bars at mid span out of which middle 2 bars are cut bars from distance of $0.15l_2$ from centre of the support**

**Provide 4-25 mm Φ bars at top of support out of which middle 2 bars are cut bars from distance of $0.3l_2$ from face of the support**

---

**Ques 6:** Design slab of the corner bed room at second floor, which is part of 5 storeyed apartment to be constructed at Ludhiana. The inside size of room is 4.25m x 5.50m.


**Answer 6:** 
### Given data

Size of room = 4.25m x5.5m

lx = 4.25m

ly = 5.5m

Assume width of support =230mm

#### 1. Calculate depth

Assume total depth of slab = 200mm

clear cover, c = 20mm **(mild exposure condition)**

Use 10mm φ bar

Eff. depth of slab

$$d_x$$ = D-c-φ/2 = 200-20-10/2 = 175mm

$$d_y$$ = D-20-φ-φ/2 = 200-20-12-12/2 = 162mm

Grade of conc. = M25

Steel = Fe 415

#### 2. Design Loads

Design load Dead load = 25 x 0.2 = 5 kN/m²

live load = 3 kN/m²
```
Factored (design) load = 1.5 (DL + LL) = 1.5 x (5 + 3) = 12kN/m^2
```

#### 3. Eff span
$$l_x$$ (Shorter span)

$$l_x$$ = 4.25 + 0.174 = 4.424m

$$l_x$$ = 4.25 + 0.23 = 4.48m

Take lower value of the above **lx = 4.424m**

$$l_y$$ (Longer span)

$$l_y$$ = 5.5 + 0.162 = 5.662m

$$l_y$$ = 5.5 + 0.23 = 5.73m

Take lower value of the above **$$l_y$$  = 5.662m**

### 4. Calculation of Moment and steel
Aspect Ratio = $$\frac{l_y}{l_x} = \frac{5.661}{4.424}$$ = 1.279

Type of Panel of moment considered - Two adjacent edges discontine

#### 4.1 Negative moment at continuous edge
$$α_x = -0.063$$  
$$a_y = -0.037$$

$$M_x = α_x.W.lx^2$$

$$= -0.063 x 12 x 4.424^2$$

**$$M_x = -14.796 kNm$$**

$$M_y = α_y.W.lx^2$$

$$ = -0.037 x 12 x 4.424^2$$

**$$M_y = -8.689 kNm$$**

$$Ast_{x} = \frac{0.5·f_{ck}}{f_y}·[1 − √\frac{1 − (4.6 · Mu)}{f_{ck}·bd_x²}].bd_x$$

$$= \frac{0.5·25}{415}·[1 − √\frac{1 − (4.6 ·-14.796 x 10^6)}{415·1000.175²}].1000.175$$

$$Ast_x = 230.56 mm^2$$

Use 12mm Ø bar

**Spacing** = $$\frac{Area 1-12 ф}{A_{st,y}} x1000 = \frac{113.09}{130.56} x 1000$$ = 490.5 mm

**Provide 12mm ф bar @300mm c/c**  Refer to Clause 26.3.3 (b) (2)

$$Ast_{y} = \frac{0.5·f_{ck}}{f_y}·[1 − √\frac{1 − (4.6 · Mu)}{f_{ck}·bd_y²}].bd_y$$

$$= \frac{0.5·25}{415}·[1 − √\frac{1 − (4.6 ·-8.689 x 10^6)}{415·1000.162²}].1000.162$$

$$Ast_y = 146.432 mm²$$

Use 12 mm ф bar

**Spacing** = $$\frac{Area 1-12 ф}{A_{st,y}} x1000 = \frac{113.09}{146.43} x 1000$$ = 772.3 mm

**Provide 12 mm ф @ 300 mm c/c**  Refer to Clause 26.3.3 (b) (2)

#### 4.2 Positive moment at midspan
$$α_x = 0.048$$  
$$a_y = 0.035$$

$$M_x = α_x.W.lx^2$$

$$= -0.048 x 12 x 4.424^2$$

**$$M_x = 11.273 kNm$$**

$$M_y = α_y.W.lx^2$$

$$= 0.035 x 12 x 4.424^2$$

**$$M_y = 8.22 kNm$$**

$$Ast_{x} = \frac{0.5·f_{ck}}{f_y}·[1 − √\frac{1 − (4.6 · Mu)}{f_{ck}.bd_x²}].bd_x$$

$$= \frac{0.5·25}{415}·[1 − √\frac{1 − (4.6 ·11.273 x 10^6)}{415·1000.175²}].1000.175$$

$$Ast_x = 182.72 mm^2$$

Use 12mm Ø bar

**Spacing** = $$\frac{Area 1-12 ф}{A_{st,y}} x1000 = \frac{113.09}{182.72} x 1000$$ = 618.9 mm

**Provide 12mm ф bar @300mm c/c**  Refer to Clause 26.3.3 (b) (2)

$$Ast_{y} = \frac{0.5·f_{ck}}{f_{y}}·[1 − √\frac{1 − (4.6 · Mu)}{f_{ck}·bd_y²}].bd_y$$

$$= \frac{0.5·25}{415}·[1 − √\frac{1 − (4.6 ·8.22 x 10^6)}{415·1000.162²}].1000.162$$

$$Ast_y = 142.693 mm²$$

Use 12 mm ф bar

**Spacing** = $$\frac{Area 1-12 ф}{A_{st,y}} x1000 = \frac{146.432}{142.693} x 1000$$ = 792.54 mm

**Provide 12 mm ф @ 300 mm c/c** Refer to Clause 26.3.3 (b) (2)

### 5. Torsion Reinforcement
Read **Clause D-1.8-1.11 Page no. 90** for torsion reinforcement.

$$A_{st,torsion} = \frac{3}{4}.A_{st} = \frac{3}{4}.182.72$$= 137.055mm²

Assume dia. of torsion rebar = 8mm

Area of 1-ϕbar = $$\frac{π}{4} x ϕ² = \frac{π}{4} x 8²$$ = 50.265mm² 

**Spacing** = $$\frac{Area of 1-ϕbar}{A_{st,torsion}} x 1000$$ = 366.75 ≈ 300mm

**Provide 8mmϕ@300mmc/c**

Generally torsion reinforcement is provided at extreme corners( not at edges over which slab is continous) within 1m distance from extreme corner and upto 1m in length.

[**Detailed Drawing**](MSE Q6.pdf)

