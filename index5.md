### Answer 5

---

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
