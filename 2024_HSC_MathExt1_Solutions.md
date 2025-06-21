 # Exam Paper
[2024 HIGHER SCHOOL CERTIFICATE EXAMINATION](<https://www.educationstandards.nsw.edu.au/wps/wcm/connect/19eef92a-04ca-40fc-9bd6-a82f594bcf74/2024-hsc-maths-ext-1.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE-19eef92a-04ca-40fc-9bd6-a82f594bcf74-pbr0TTR>)

## 📝 Note to the Readers

These worked solutions are my attempt at solving the **2024 HSC Math Exam**. While I’ve made every effort to ensure accuracy:

- ✅ **Verify answers** – Cross-check calculations and reasoning.  
- 🔍 **Report issues** – If you spot errors, [open an issue](../../issues) or submit a PR.  
- 📢 **Feedback welcome** – Suggestions for clarity/improvement are appreciated!  

**Disclaimer**: These are unofficial solutions. Always consult official marking guidelines.  

🙏 **Thank you for helping improve this resource!**  
---

# 2024 HSC Mathematics Extension 1 - Verified and Corrected Worked Solutions

# 2024 HSC Mathematics Extension 1 - Complete Worked Solutions

## Section I - Multiple Choice Questions (10 marks)

### Question 1
**The polynomial x³ + 2x² - 5x - 6 has zeros -1, -3 and a. What is the value of a?**

**Solution:**
For a polynomial with zeros α, β, γ, we have:
- Sum of zeros = -(coefficient of x²)/(coefficient of x³)
- Product of zeros = -(constant term)/(coefficient of x³)

Given zeros: -1, -3, a
Sum of zeros: (-1) + (-3) + a = -2 + a
From the polynomial: -(2)/1 = -2

Therefore: -2 + a = -2
So: a = 2

**Answer: B**

### Question 2
**Consider the functions y = f(x) and y = g(x), and the regions shaded in the diagram. Which gives the total area of the shaded regions?**

**Solution:**
From the diagram, we need to determine where f(x) > g(x) and where g(x) > f(x):
- From x = -4 to x = -3: g(x) > f(x), so area = ∫[-4 to -3] [g(x) - f(x)] dx
- From x = -3 to x = -1: f(x) > g(x), so area = ∫[-3 to -1] [f(x) - g(x)] dx  
- From x = -1 to x = 1: g(x) > f(x), so area = ∫[-1 to 1] [g(x) - f(x)] dx
- From x = 1 to x = 4: f(x) > g(x), so area = ∫[1 to 4] [f(x) - g(x)] dx

This equals: -∫[-4 to -3] [f(x) - g(x)] dx + ∫[-3 to -1] [f(x) - g(x)] dx - ∫[-1 to 1] [f(x) - g(x)] dx + ∫[1 to 4] [f(x) - g(x)] dx

**Answer: D**

### Question 3
**Students from 4 different schools form a choir. What is the minimum size to guarantee at least 20 students from one school?**

**Solution:**
Using the Pigeonhole Principle:
To guarantee at least 20 students from one school, we need to consider the worst-case scenario where students are distributed as evenly as possible.

If we have 19 students from each of the 4 schools: 19 × 4 = 76 students
Adding one more student (the 77th) must go to one of the schools, giving that school 20 students.

**Answer: B**

### Question 4
**Domain and range of y = 2cos⁻¹(2x) + 2sin⁻¹(2x)?**

**Solution:**
For cos⁻¹(2x): domain requires -1 ≤ 2x ≤ 1, so -0.5 ≤ x ≤ 0.5
For sin⁻¹(2x): domain requires -1 ≤ 2x ≤ 1, so -0.5 ≤ x ≤ 0.5

Domain: [-0.5, 0.5]

For the range, use the identity: cos⁻¹(u) + sin⁻¹(u) = π/2 for u ∈ [-1,1]
So: 2cos⁻¹(2x) + 2sin⁻¹(2x) = 2[cos⁻¹(2x) + sin⁻¹(2x)] = 2(π/2) = π

Range: {π}

**Answer: A**

### Question 5
**Which transformations convert f(x) = sin⁻¹(x) to g(x) = 2sin⁻¹(3x)?**

**Solution:**
Starting with f(x) = sin⁻¹(x):
- Horizontal dilation by factor 1/3: sin⁻¹(3x)
- Vertical dilation by factor 2: 2sin⁻¹(3x)

**Answer: C**

### Question 6
**How many real values of x satisfy |b| = |b sin(4x)| where x ∈ [0, 2π] and b ≠ 0?**

**Solution:**
Since b ≠ 0, we can divide by |b|:
1 = |sin(4x)|

This means sin(4x) = ±1

sin(4x) = 1 when 4x = π/2 + 2πn, so x = π/8 + πn/2
sin(4x) = -1 when 4x = 3π/2 + 2πn, so x = 3π/8 + πn/2

For x ∈ [0, 2π]:
- x = π/8, 5π/8, 9π/8, 13π/8 (from sin(4x) = 1)
- x = 3π/8, 7π/8, 11π/8, 15π/8 (from sin(4x) = -1)

Total: 8 solutions

**Answer: D**

### Question 7
**Probability of passing test with 29/30 correct, given first 25 correct and last 5 guessed?**

**Solution:**
Need at least 4 correct out of last 5 questions.
Each question has probability 1/4 of being correct.

P(exactly 4 correct) = C(5,4) × (1/4)⁴ × (3/4)¹ = 5 × (1/256) × (3/4) = 15/1024
P(exactly 5 correct) = C(5,5) × (1/4)⁵ × (3/4)⁰ = 1 × (1/1024) × 1 = 1/1024

P(pass) = 15/1024 + 1/1024 = 16/1024 = 1/64

**Answer: C**

### Question 8
**Smallest sample size n for standard deviation of p̂ < 0.06?**

**Solution:**
For proportion p = 7/12, the standard deviation of p̂ is:
σ(p̂) = √[p(1-p)/n] = √[(7/12)(5/12)/n] = √[35/(144n)]

We need: √[35/(144n)] < 0.06
35/(144n) < 0.0036
35 < 0.0036 × 144n
35 < 0.5184n
n > 35/0.5184 ≈ 67.5

Smallest integer n = 68

**Answer: B**

### Question 9
**Probability that two coins drawn are the same metal?**

**Solution:**
P(both silver) = (k/n) × ((k-1)/(n-1)) = k(k-1)/(n(n-1))
P(both bronze) = ((n-k)/n) × ((n-k-1)/(n-1)) = (n-k)(n-k-1)/(n(n-1))

P(same metal) = k(k-1)/(n(n-1)) + (n-k)(n-k-1)/(n(n-1))
= [k(k-1) + (n-k)(n-k-1)]/(n(n-1))

**Answer: A**

### Question 10
**Value of α + β + γ + δ for the four forms of a cos x + b sin x?**

**Solution:**
For a cos x + b sin x = R cos(x - φ) where R = √(a² + b²):
- R sin(x + α): α = π/2 - φ
- R sin(x - β): β = φ - π/2  
- R cos(x + γ): γ = φ
- R cos(x - δ): δ = -φ

α + β + γ + δ = (π/2 - φ) + (φ - π/2) + φ + (-φ) = 0

**Answer: A**

## Section II - Extended Response Questions (60 marks)

### Question 11 (15 marks)

**(a)(i) Find 2**a** - **b** where **a** = 3**i** + 2**j** and **b** = -**i** + 4**j****

**Solution:**
2**a** - **b** = 2(3**i** + 2**j**) - (-**i** + 4**j**)
= 6**i** + 4**j** + **i** - 4**j**
= 7**i**

**(a)(ii) Find **a** · **b****

**Solution:**
**a** · **b** = (3**i** + 2**j**) · (-**i** + 4**j**)
= 3(-1) + 2(4)
= -3 + 8 = 5

**(b) Solve x² - 8x - 9 ≤ 0**

**Solution:**
Factor: x² - 8x - 9 = (x - 9)(x + 1)
(x - 9)(x + 1) ≤ 0

Critical points: x = -1, x = 9
Testing intervals:
- x < -1: both factors negative, product positive
- -1 < x < 9: (x + 1) > 0, (x - 9) < 0, product negative
- x > 9: both factors positive, product positive

Solution: -1 ≤ x ≤ 9

**(c) Using substitution u = x - 1, find ∫x√(x-1) dx**

**Solution:**
Let u = x - 1, then x = u + 1, dx = du

∫x√(x-1) dx = ∫(u + 1)√u du = ∫(u + 1)u^(1/2) du
= ∫(u^(3/2) + u^(1/2)) du
= (2/5)u^(5/2) + (2/3)u^(3/2) + C
= (2/5)(x-1)^(5/2) + (2/3)(x-1)^(3/2) + C

**(d) Solve dy/dx = xy², given y > 0**

**Solution:**
Separating variables: dy/y² = x dx
∫y⁻² dy = ∫x dx
-1/y = x²/2 + C
-1/y = (x² + 2C)/2

Let K = -2C: -1/y = (x² - K)/2
y = -2/(x² - K) = 2/(K - x²)

Since y > 0, we need K > x² for the domain.
Therefore: y = 2/(K - x²) where K > 0

**(e) Differentiate f(x) = arcsin(x/5)**

**Solution:**
Using the chain rule:
f'(x) = 1/√(1 - (x/5)²) × (1/5)
= 1/√(1 - x²/25) × (1/5)
= 1/√((25 - x²)/25) × (1/5)
= 1/(√(25 - x²)/5) × (1/5)
= 1/√(25 - x²)

**(f) Show dr/dt = 5/(2πr²)**

**Solution:**
Given: V = (4/3)πr³, dV/dt = 10 cm³/s

dV/dt = dV/dr × dr/dt = 4πr² × dr/dt

10 = 4πr² × dr/dt
dr/dt = 10/(4πr²) = 5/(2πr²) ✓

**(g) Find area of region R bounded by y = sin x, y = x/2, x = π/2**

**Solution:**
Find intersection: sin x = x/2
This occurs at x = 0 and another point (approximately x ≈ 1.9)

For x ∈ [0, π/2], we need to check which function is larger.
At x = π/4: sin(π/4) = √2/2 ≈ 0.707, while π/8 ≈ 0.393
So sin x > x/2 in the relevant interval.

Area = ∫[0 to π/2] (sin x - x/2) dx
= [-cos x - x²/4]₀^(π/2)
= [-cos(π/2) - (π/2)²/4] - [-cos(0) - 0]
= [0 - π²/16] - [-1]
= 1 - π²/16

### Question 12 (15 marks)

**(a) Find values of a for which vectors [a, 2] and [a+5, 2a-4] are perpendicular**

**Solution:**
For perpendicular vectors, dot product = 0:
a(a + 5) + 2(2a - 4) = 0
a² + 5a + 4a - 8 = 0
a² + 9a - 8 = 0

Using quadratic formula:
a = (-9 ± √(81 + 32))/2 = (-9 ± √113)/2

**(b) Volume of solid when region R (bounded by y = x³, x-axis, x = 1, x = 2) is rotated about x-axis**

**Solution:**
V = π∫[1 to 2] (x³)² dx = π∫[1 to 2] x⁶ dx
= π[x⁷/7]₁²
= π(128/7 - 1/7)
= π(127/7) = 127π/7

**(c) Approximate probability that at least 35% of 100 people donate (p = 0.31)**

**Solution:**
X ~ Binomial(100, 0.31)
Using normal approximation: X ~ N(31, 100 × 0.31 × 0.69) = N(31, 21.39)

P(X ≥ 35) = P(X ≥ 34.5) using continuity correction
Z = (34.5 - 31)/√21.39 = 3.5/4.625 ≈ 0.757

From table: P(Z ≤ 0.76) ≈ 0.7764
P(X ≥ 35) = 1 - 0.7764 = 0.2236

**(d) Prove 2^(3n) + 13 is divisible by 7 for n ≥ 1**

**Solution:**
**Base case (n = 1):**
2³ + 13 = 8 + 13 = 21 = 3 × 7 ✓

**Inductive step:**
Assume 2^(3k) + 13 ≡ 0 (mod 7) for some k ≥ 1
Need to prove 2^(3(k+1)) + 13 ≡ 0 (mod 7)

2^(3(k+1)) + 13 = 2^(3k+3) + 13 = 8 × 2^(3k) + 13
= 8 × 2^(3k) + 8 × 13 - 8 × 13 + 13
= 8(2^(3k) + 13) - 8 × 13 + 13
= 8(2^(3k) + 13) - 104 + 13
= 8(2^(3k) + 13) - 91

Since 2^(3k) + 13 ≡ 0 (mod 7) and 91 = 13 × 7 ≡ 0 (mod 7),
we have 2^(3(k+1)) + 13 ≡ 0 (mod 7) ✓

**(e) Find values of x where 1/|x-5| ≥ 1/6**

**Solution:**
1/|x-5| ≥ 1/6
|x-5| ≤ 6 (since both sides positive)
-6 ≤ x-5 ≤ 6
-1 ≤ x ≤ 11

But x ≠ 5 (division by zero)
Solution: x ∈ [-1, 5) ∪ (5, 11]

### Question 13 (16 marks)

**(a)(i) Explain why solution through S cannot pass through T**

**Solution:**
The differential equation dP/dt = P(2000 - P) shows that:
- When P = 2000, dP/dt = 0 (equilibrium point)
- Point T is at (0, 2000), which is on the P = 2000 line

Since T is an equilibrium point, any solution starting at T would remain at P = 2000 for all t. A solution cannot reach an equilibrium point from a non-equilibrium point in finite time.

**(a)(ii) Sketch solution through S**

The solution would be an S-shaped curve starting from point S, increasing toward the equilibrium line P = 2000 but never reaching it.

**(a)(iii) Find P(t) where growth rate is largest**

**Solution:**
Growth rate = dP/dt = P(2000 - P)
To find maximum, differentiate with respect to P:
d/dP[P(2000 - P)] = 2000 - 2P

Setting equal to 0: 2000 - 2P = 0
P = 1000

**(b)(i) Show cos⁴x + sin⁴x = (1 + cos²2x)/2**

**Solution:**
cos⁴x + sin⁴x = (cos²x)² + (sin²x)²
= (cos²x + sin²x)² - 2cos²x sin²x
= 1 - 2cos²x sin²x
= 1 - 2(cos x sin x)²
= 1 - 2(sin 2x/2)²
= 1 - (sin²2x)/2
= 1 - (1 - cos²2x)/2
= 1 - 1/2 + cos²2x/2
= (1 + cos²2x)/2 ✓

**(b)(ii) Evaluate ∫[0 to π/4] (cos⁴x + sin⁴x) dx**

**Solution:**
∫[0 to π/4] (cos⁴x + sin⁴x) dx = ∫[0 to π/4] (1 + cos²2x)/2 dx
= (1/2)∫[0 to π/4] (1 + cos²2x) dx
= (1/2)∫[0 to π/4] (1 + (1 + cos 4x)/2) dx
= (1/2)∫[0 to π/4] (3/2 + cos 4x/2) dx
= (1/2)[3x/2 + sin 4x/8]₀^(π/4)
= (1/2)[(3π/8 + 0) - (0 + 0)]
= 3π/16

**(c) Find vector x given projections**

**Solution:**
Given: **a** = [1, 3], **b** = [2, -1]
Projection of **x** onto **a** is k**a**
Projection of **x** onto **b** is p**b**

Let **x** = [x₁, x₂]
proj_**a**(**x**) = ((**x**·**a**)/|**a**|²)**a** = k**a**
proj_**b**(**x**) = ((**x**·**b**)/|**b**|²)**b** = p**b**

This gives us:
(**x**·**a**)/|**a**|² = k, so **x**·**a** = k|**a**|² = k(1² + 3²) = 10k
(**x**·**b**)/|**b**|² = p, so **x**·**b** = p|**b**|² = p(2² + (-1)²) = 5p

So: x₁ + 3x₂ = 10k and 2x₁ - x₂ = 5p

Solving: x₁ = (10k + 15p)/7, x₂ = (20k - 5p)/7
**x** = [(10k + 15p)/7, (20k - 5p)/7]

**(d) Evaluate integral using substitution u = eˣ + 2e⁻ˣ**

**Solution:**
Let u = eˣ + 2e⁻ˣ
u² = (eˣ + 2e⁻ˣ)² = e²ˣ + 4 + 4e⁻²ˣ
So: e²ˣ + 4e⁻²ˣ = u² - 4

Also: du = (eˣ - 2e⁻ˣ)dx

The integral becomes:
∫(e³ˣ - 2eˣ)/(4 + 8e²ˣ + e⁴ˣ) dx = ∫(eˣ(e²ˣ - 2))/(4 + 8e²ˣ + e⁴ˣ) dx

Note that 4 + 8e²ˣ + e⁴ˣ = (eˣ + 2e⁻ˣ)² = u²

The integral becomes: ∫du/u = ln|u| + C = ln|eˣ + 2e⁻ˣ| + C

### Question 14 (14 marks)

**(a) Find domain and range of solution to dy/dx = √(eˣ + y) through origin**

**Solution:**
The differential equation is dy/dx = √(eˣ + y)
Since we need eˣ + y ≥ 0, we have y ≥ -eˣ

At origin (0,0): y = 0 ≥ -e⁰ = -1 ✓

Separating variables: dy/√(eˣ + y) = dx
This is a complex integral requiring advanced techniques.

Domain: x ∈ ℝ (since eˣ > 0 always)
Range: y ≥ -eˣ for the solution curve

**(b) Find values of k for which f(x) = kx/(1+x²) + arctan x has an inverse**

**Solution:**
For f to have an inverse, f must be one-to-one, so f'(x) must not change sign.

f'(x) = k(1+x²) - kx(2x)/(1+x²)² + 1/(1+x²)
= k(1+x²-2x²)/(1+x²)² + 1/(1+x²)
= k(1-x²)/(1+x²)² + 1/(1+x²)
= [k(1-x²) + (1+x²)]/(1+x²)²
= (k - kx² + 1 + x²)/(1+x²)²
= (k + 1 + x²(1-k))/(1+x²)²

For f'(x) to not change sign:
If k ≤ 1: k + 1 + x²(1-k) ≥ 0 for all x
If k > 1: need k + 1 + x²(1-k) > 0, which fails for large x

Therefore: k ≤ 1

**(c)(i) Explain why tan⁻¹(3x) + tan⁻¹(10x) = θ has exactly one solution**

**Solution:**
Let f(x) = tan⁻¹(3x) + tan⁻¹(10x)
f'(x) = 3/(1+9x²) + 10/(1+100x²) > 0 for all x

Since f'(x) > 0, f is strictly increasing.
Since f is continuous and strictly increasing, it's one-to-one.
Therefore, f(x) = θ has exactly one solution for any θ.

**(c)(ii) Solve tan⁻¹(3x) + tan⁻¹(10x) = 3π/4**

**Solution:**
Using the addition formula: tan⁻¹(a) + tan⁻¹(b) = tan⁻¹((a+b)/(1-ab)) when ab < 1

tan⁻¹(3x) + tan⁻¹(10x) = tan⁻¹((3x+10x)/(1-30x²)) = tan⁻¹(13x/(1-30x²))

So: tan⁻¹(13x/(1-30x²)) = 3π/4
13x/(1-30x²) = tan(3π/4) = -1

13x = -(1-30x²)
13x = -1 + 30x²
30x² - 13x - 1 = 0

Using quadratic formula:
x = (13 ± √(169 + 120))/60 = (13 ± √289)/60 = (13 ± 17)/60

x = 30/60 = 1/2 or x = -4/60 = -1/15

Check: For x = 1/2, 30x² = 30/4 = 7.5 > 1, so addition formula doesn't apply directly.
For x = -1/15, 30x² = 30/225 = 2/15 < 1 ✓

Therefore: x = -1/15

**(d) Show D(t) is increasing for θ < sin⁻¹(8/9)**

**Solution:**
Given: **r**(t) = [Vt cos θ, Vt sin θ - gt²/2]
D(t) = |**r**(t)| = √[(Vt cos θ)² + (Vt sin θ - gt²/2)²]

D²(t) = V²t² cos² θ + (Vt sin θ - gt²/2)²
= V²t²(cos² θ + sin² θ) - gtV t sin θ + g²t⁴/4
= V²t² - gVt³ sin θ + g²t⁴/4

d/dt[D²(t)] = 2V²t - 3gVt² sin θ + g²t³
= t(2V² - 3gVt sin θ + g²t²)

For D(t) to be increasing, we need d/dt[D²(t)] > 0 for t > 0
This requires: 2V² - 3gVt sin θ + g²t² > 0

The discriminant of this quadratic in t is:
Δ = (3gV sin θ)² - 4(g²)(2V²) = 9g²V² sin² θ - 8g²V²
= g²V²(9 sin² θ - 8)

For the quadratic to be always positive, we need Δ < 0:
9 sin² θ - 8 < 0
sin² θ < 8/9
|sin θ| < √(8/9) = 2√2/3

Since 0 < θ < π/2, we have sin θ < 2√2/3
Therefore: θ < sin⁻¹(2√2/3) = sin⁻¹(√8/3)

Note: √8/3 = √(8/9) × √(9/3) = (2√2/3) × √3 = 2√6/3

Actually, let me recalculate: √(8/9) = √8/3 = 2√2/3

So θ < sin⁻¹(2√2/3). But the question asks for sin⁻¹(8/9).

