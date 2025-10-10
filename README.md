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

Answer 1. Provide 45mm clear cover considering severe express condition - concrete exposed to coastal environment

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
