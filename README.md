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

MSE-1
Date: 

Quest 1: What clear cover be provided for a beam which is part of a bridge deck to be constructed over the Arabian Sea, along the western cost of Mumbai.

Answer 1. Provide 50mm clear cover considering very severe condition - concrete exposed to coastal environment Acc. to table no. 16, IS 456 : 2000

Ques 2: Analysis for the maximum BM to be considered for the design of the landing slab of a staircase shown in the figure, taking total design lead on landing and flight as 10 KN/m², X = 0.45m, Y = 0.6m & G=2.5m. Clear width of staircase is 2.4m and brick walls supporting Staircase have thickness of 250m.

<img width="1536" height="1024" alt="Stairs" src="https://github.com/user-attachments/assets/1f131076-5ea4-4ae4-bdf0-4f12d1c30c16" />
   
Answer 2. 

# 📋 Given Data

| Parameter                                | Value  | Unit    |
|-----------------------------------------:|:------:|:-------:|
| Total design load on landing and flight/going | 10     | kN/m²  |
| Landing X Dimension                      | 0.45   | m       |
| Landing Y Dimension                      | 0.60   | m       |
| Going (G)                                | 2.50   | m       |
| Clear Width                              | 2.40   | m       |
| Brick Wall Thickness                     | 250    | mm      |

---

## 🧮 Step 1: Determine Effective Span
The effective span is calculated as the sum of the going and the two landing dimensions.

Formula:
```
Effective Span = G + X + Y
```

Calculation:
```
Effective Span = 2.5 + 0.45 + 0.6 = 3.55 m
```

---

## 📊 Step 2: Calculate Loads

A. Load Intensity

- Load on Going: 10 kN/m²
- Load on Landing (50% assumed to act horizontally): 10 / 2 = 5 kN/m²

B. Total Load Calculation

- Load directly on landing:
```
10 kN/m² × (0.6 m + 0.45 m) = 10 × 1.05 = 10.5 kN/m
```

- Load from going:
```
10 kN/m² × 2.5 m = 25.0 kN/m  ← Note: if the going area considered is 2.5 m width × 1 m run, the result is 25.0 kN/m.
```
(However the original calculation gave 12.5 kN/m — if that assumed 50% of going load or a different width, clarify the load distribution. Below we follow the original given numbers.)

Using the original provided values:
```
Load from going (as given) = 12.5 kN/m
```

- Total Load:
```
Total Load = 10.5 + 12.5 = 23.0 kN/m
```

C. Load per Meter Width
```
w = 23.0 kN/m ÷ 2.4 m = 9.58 kN/m
```

---

## 📐 Step 3: Final Effective Span for Bending Moment
A different effective span is used for the bending moment calculation, considering the double flight and support width.

Formula:
```
Effective Span = (2 × Clear Width) + Support Width
```

Calculation (support width taken as 0.1 m):
```
Effective Span = (2 × 2.4) + 0.1 = 4.9 m
```

---

## 💡 Step 4: Calculate Maximum Bending Moment
For a simply supported beam with uniformly distributed load, the maximum bending moment at midspan is:
```
Mu = w × l² / 8
```

Calculation:
```
w = 9.58 kN/m
l = 4.9 m

Mu = 9.58 × (4.9)² / 8
   = 9.58 × 24.01 / 8
   = 229.98 / 8
   = 28.75 kNm
```

---

## ✅ Final Result
The design maximum bending moment at midspan of the landing is:

**Mu = 28.75 kNm**

Ques 3. Design stairs consisting of independent steps project from the face of RCC wall. The stairs will be part of a mall be constructed in Goa.

Answer 3: 

# Assumptions
- Width of flight = 1.5 m  
- Riser = 150 mm  
- Tread = 300 mm  
- Grade of concrete = M20, fck = 20 N/mm²  
- Grade of steel = Fe 415, fy = 415 N/mm²

---

# Solution

- It is desirable to make the actual width of the tread slab, B, about 10 mm more than the effective tread, so that there is a marginal overlap between adjacent tread slabs.  
  - B = 310 mm

- Assume a slab thickness at the fixed support, t = 150 mm.  
  - The slab thickness may be kept constant for a distance of, say, 300 mm from the support and tapered to a minimum thickness of 80 mm (as shown in the referenced figure).

---

## 1. Design loads

### 1.1 Dead loads
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

Page 3:
```
Wu, DL = 1.348 × 1.5 = 2.022 kN/m
```

### 1.2 Live load
(i) Alternative I:
```
Wu, LL = 5.0 × 0.3 × 1.5 = 2.250 kN/m
```

(ii) Alternative II:
```
Wu, LL = 1.3 × 1.5 = 1.95 kN  (at free end)
```

---

## Design & Moments

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

---

## Design of Main Bars

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

---

## Design of Distribution Bars

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

---

## Summary / Provided reinforcement
- Main reinforcement: 3 nos. 10 mm Ø bars (Ast provided = 235.6 mm²)  
- Distribution bars: 8 mm Ø @ 270 mm c/c

<img width="1536" height="1024" alt="tread stairs" src="https://github.com/user-attachments/assets/37047e88-620b-4337-a31c-a98487cbf51c" />

# Ques 4 — Design shear forces and bending moments (as per IS 456)

Find design shear forces and bending moments at critical sections of a five-span continuous reinforced beam supported on masonry supports of 300 mm each.  
Clear spans from left to right: 4.5 m, 4.75 m, 5.0 m, 4.75 m, 4.5 m.  
Beam loading: dead load (including self weight) = 60 kN/m and imposed (live) load at service level = 30 kN/m.

<img width="810" height="252" alt="image" src="https://github.com/user-attachments/assets/525c9de1-a2b2-4470-88d0-5b593c2c9492" />


---

## Given data

- Clear spans (left → right): 4.5 m, 4.75 m, 5.0 m, 4.75 m, 4.5 m  
- Support width (masonry): 300 mm = 0.30 m  
- Dead load (service): 60 kN/m (incl. self weight)  
- Imposed (live) load (service): 30 kN/m

---

## Design (factored) uniformly distributed loads (using 1.5 load factor)

```
Wu,DL = 60 × 1.5 = 90 kN/m
Wu,LL = 30 × 1.5 = 45 kN/m
```

Total factored UDL (where needed) = 90 + 45 = 135 kN/m

---

## Effective spans (clear span + support width)

(Use support width = 0.30 m added to the clear span at the relevant span)

```
For 4.5 m span: 4.5 + 0.3 = 4.8 m
For 4.75 m span: 4.75 + 0.3 = 5.05 m
For 5.0 m span: 5.0 + 0.3 = 5.3 m
```

---

## Shear Forces

1. At end supports (SF1)
```
SF1 = ((0.4 × 90) + (0.45 × 45)) × 4.8 = 270 kN
```

2. At supports next to the end supports

2.1 Outer side (SF2)
```
SF2 = ((0.5 × 90) + (0.6 × 45)) × 4.8 = 388.8 kN
```

2.2 Inner side (SF3)
```
SF3 = ((0.55 × 90) + (0.6 × 45)) × 5.05 = 386.325 kN
```

3. At all other interior supports (SF4)
```
SF4 = ((0.5 × 90) + (0.6 × 45)) × 5.3 = 381.6 kN
```

---

## Bending Moments

1. Span moments (example: near middle of end span)
```
(Moment formula as used)
Mu = (Wu,DL + Wu,LL) × l²  = (90 + 45) × 4.8²  = 276.48 kNm
```
# Effective span and Support Moments

- Effective span
- Support Moments
- 2 Support Moments
- At support next to Open
- At other Interior support

## M5

- 4.8 — 322.5 Nm
- 5.5² — 551105 kN·m

# Ques 5 — Design of 2nd span of continuous beam of question 4.

## Given
- Clear span (2nd span): 4.75 m  
- Support width: 0.30 m  
- Effective span, l = 4.75 + 0.30 = 5.05 m  
- Assumed overall dimensions: b = 300 mm, d = 500 mm  
- Provided bar considered: 25 mm Ø (area of one 25 mm bar = 490.87 mm²)  
- Material properties and moments are used as given in the problem statements below.

---

## Calculation of steel required (mid-span / as given)

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

## Summary / Recommendation
- For the 2nd span (as computed) provide: 4 nos. of 25 mm Ø main reinforcement (Ast provided = 1963.48 mm²).
