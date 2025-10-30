### Answer 6

---

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
