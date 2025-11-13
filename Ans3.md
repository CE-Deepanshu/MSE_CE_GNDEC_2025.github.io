## Answer 3

---

### Assumptions
- Width of flight = 1.5 m  
- Riser = 150 mm  
- Tread = 300 mm  
- Grade of concrete = M20, fck = 20 N/mm²  
- Grade of steel = Fe 415, fy = 415 N/mm²

### Solution
 Assume a slab thickness at the fixed support, t = 150 mm.  
  - The slab thickness may be kept constant for a distance of, say, 300 mm from the support and tapered to a minimum thickness of 80 mm (as shown in the referenced figure).

#### 1. Design loads

##### 1.1 Dead loads
(1) Self weight of tread slab = 25 × (0.15 × 0.3) = 1.125 kN/m (Refer to Clause 19.2, Page No. 32, IS 456)  

(2) Finishes = 0.6 × 0.31 = 0.186 kN/m (Refer Table No. 2, Part-1, Page No. 30, IS 875 : 1987)

Total dead load, DL = 1.125 + 0.186 = 1.311 kN/m

```
Wu,DL = 1.311 × 1.5 = 1.966 kN/m
```

##### 1.2 Live load
###### **(i) Load Case I:**

The Loading Code **[IS 875 : 1987 (Part II)]** recommends a uniformly distributed load of 5.0 kN/m2 in general, on the going, as well as the landing. 

```
Wu,LL1 = 5.0 × 0.3 × 1.5 = 2.250 kN/m
```
###### **(ii) Load Case II:**
```
Wu,LL2 = 1.3 × 1.5 = 1.95 kN/m (at free end)
```
#### 2. Design Moments

- Moment at fixed end due to dead load:

Mu,DL = (1.966 × 1.5²)/ 2 = 2.211 kNm

- Moments due to live load (considering alternatives):

Mu,LL - Load Case 1 = (2.25 × 1.5²)/ 2 = 2.53 kNm

Mu,LL - Load Case 2 = 1.95 × 1.5 = 2.93 kNm  (more critical)
  
-Total design bending moment at fixed end:
```
Mu = Mu,DL + Mu,LL = 2.211 + 2.93 = 5.141 ~ 5.2 kNm
```

#### 3. Design of Main Bars

Assume clear cover = 20 mm **(mild exposure)** and bar diameter = 10 mm.  
**Effective depth:**

d = 150 - 20 - 10/2 = 125 mm

**Required main steel area (Ast) using the following expression:**
```
Ast,required = 0.5.fck/fy x (1-√(1-((4.6.Mu x 10^6)/(fck.b.d^2)))) x b x d
             = 0.5 x 20/415 x (1-√(1-((4.6 x 5.2 x 10^6)/(20 x 300 x 125^2)))) x 300 x 125
Ast,required = 123.75 mm² ~ 124 mm²

Provide main bars of 10 mm dia.

Area of one 10Φ = π/4 × 10² = 78.54 mm²

No. of bars = Ast,required/ Area of one 10Φ = 124/ 78.54 = 3 No.

Ast,provided = 3 × 78.54 = 235.62 mm²  ~ 124 mm²
```
**Provide Main bars 8 mm Φ @ 270 mm c/c**

#### 4. Design of Distribution Bars

**Minimum steel for distribution bars:**
```
Ast,min. = 0.12% × b × d = 0.12% × 310 × 125 = 180 mm²
Provide 8 mm bar:
Area of one 8Φ = π/4 × 8² = 50.27 mm²  (approx)

Spacing = Area of one 8Φ/ Ast,min. x 1000
            = 50.27 mm²/ 180 x 1000  = 278.88 mm
```
**Provide Distribution bars 8 mm Φ @ 270 mm c/c**

#### ✅ 5. Design Summary 
**Grade of Concrete : M20**

**Grade of Steel : Fe415**

**Clear Cover : 20mm**

**Main reinforcement: 3 nos. 10 mm Ø bars (Ast provided = 235.6 mm²)**

**Distribution bars: 8 mm Ø @ 270 mm c/c**

<img width="1242" height="396" alt="image" src="https://github.com/user-attachments/assets/b23de724-5717-4adc-a532-906ba0718b40" />
