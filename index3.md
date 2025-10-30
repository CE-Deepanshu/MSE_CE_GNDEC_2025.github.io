### Answer 3

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
