## Answer 4
---
### Given data

- Clear spans (left → right): 4.5 m, 4.75 m, 5.0 m, 4.75 m, 4.5 m  
- Support width (masonry): 300 mm = 0.30 m  
- Dead load (service): 60 kN/m (incl. self weight)  
- Imposed (live) load (service): 30 kN/m

### Solution

#### **1. Design (factored) uniformly distributed loads (using 1.5 load factor)**
```
Wu,DL = 60 × 1.5 = 90 kN/m

Wu,LL = 30 × 1.5 = 45 kN/m

Total factored UDL (where needed) = 90 + 45 = 135 kN/m
```
#### **2. Effective spans (clear span + support width)**
```
(Use support width = 0.30 m added to the clear span at the relevant span as we don't know about effective depth)

For 4.5 m span: 4.5 + 0.3 = 4.8 m
For 4.75 m span: 4.75 + 0.3 = 5.05 m
For 5.0 m span: 5.0 + 0.3 = 5.3 m
```
#### **3. Shear Forces**
**Use Formula**
```
SF = Coeff.Wu,DL + Coeff.Wu,LL x l

For Example : ((0.4 × Wu_DL) + (0.45 × Wu_LL)) × 4.8
```
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
```
Mu = (Wu,DL/12 + Wu,LL/10) × l^2 
```
**1. Span moments** 

**1.1 Near middle of end span**

M1 = (Wu,DL/12 + Wu,LL/10) × l^2  = (90/12 + 45/10) × 4.8^2 = 276.48 kNm

**1.2 At middle of interior span**

M2 = (Wu,DL/16 + Wu,LL/12) × l^2  = (Wu,90/12 + 45/10) × 5.05^2 = 239.1 kNm

M3 = (Wu,DL/16 + Wu,LL/12) × l^2  = (Wu,90/16 + 45/12) × 5.3^2 = 263.34 kNm

**1. Support moments** 

**At support next to the end supports**

\[\M4 = -(\frac{Wu_DL}{10} + Wu,LL/9) × l^2 = -(90/10 + 45/9) × 4.8^2 = -322.56 kNm\]

**At support next to the end supports**

M5 = -(Wu,DL/12 + Wu,LL/9) × l^2  =  -(90/12 + 45/9) × 5.3^2 = -351.125 kNm
```
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
</script>
    
<script type="text/javascript"
        src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
```
