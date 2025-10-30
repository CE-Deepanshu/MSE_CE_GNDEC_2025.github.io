## Answer 2

---

### Given Data

| Parameter                                | Value  | Unit    |
|-----------------------------------------:|:------:|:-------:|
| Total design load on landing and flight/going | 10     | kN/m²  |
| Landing X Dimension                      | 0.45   | m       |
| Landing Y Dimension                      | 0.60   | m       |
| Going (G)                                | 2.50   | m       |
| Clear Width of staircase                             | 2.40   | m       |
| Brick Wall Thickness                     | 250    | mm      |

#### Step 1: Determine Effective depth (Refer Clause 23.21 (a) for simply supported beam, IS 456 : 2000)
Calculation
```
centre to centre distance between landings = X+G+Y = 0.45+2.5+0.6 = 3.55m=3550 mm
Thickness of slab = 3550/20 = 177.5~180 mm
Assume dia. of bar 12 mm and clear cover 20 mm (mild exposure condition), the effective depth(d)= 180-20-12/2 = 154 mm
```
#### Step 2: Determine Effective Span (Refer Clause 22.2 (a), IS 456 : 2000)
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
##### ✅ Effective span
```
Consider effective span which is lesser in the above value
Effective span of landing slab, Leff. = 2.554 m
```
#### Step 3: Calculate Loads acting on landing (assumed to be uniformly distributed)

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
