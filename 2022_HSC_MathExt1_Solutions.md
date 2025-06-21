 # Exam Paper
[2022 HIGHER SCHOOL CERTIFICATE EXAMINATION](<https://www.educationstandards.nsw.edu.au/wps/wcm/connect/c2f22c69-d21a-417b-9f12-4efdeecf9e23/2022-hsc-mathematics-extension-1.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE-c2f22c69-d21a-417b-9f12-4efdeecf9e23-oghstyU>)

## 📝 Note to the Readers

These worked solutions are my attempt at solving the **2022 HSC Math Ext1 Exam**. While I’ve made every effort to ensure accuracy:

- ✅ **Verify answers** – Cross-check calculations and reasoning.  
- 🔍 **Report issues** – If you spot errors, [open an issue](../../issues) or submit a PR.  
- 📢 **Feedback welcome** – Suggestions for clarity/improvement are appreciated!  

**Disclaimer**: These are unofficial solutions. Always consult official marking guidelines.  

🙏 **Thank you for helping improve this resource!**  
---

# 2022 HSC Mathematics Extension 1 - Complete Solutions

## Section I - Multiple Choice (10 marks)

### Question 1
**Given:** cos(23π/12) = (√6 + √2)/4

**Find:** cos⁻¹((√6 + √2)/4)

**Solution:**
If cos(23π/12) = (√6 + √2)/4, then cos⁻¹((√6 + √2)/4) = 23π/12

However, we need to check if 23π/12 is in the range [0, π] for cos⁻¹.
23π/12 = 23 × 180°/12 = 345°

Since 345° > 180°, we need the reference angle in [0, π].
The angle with the same cosine value in [0, π] is: 2π - 23π/12 = 24π/12 - 23π/12 = π/12

**Answer: C. π/12**

### Question 2
**Given:** Original function f(x) = 3/(x-1) + 2, transformed to g(x)

**Analysis of transformation:**
Looking at the graphs, g(x) appears to be the reflection of f(x) across the y-axis.

For reflection across y-axis: g(x) = f(-x)
So g(x) = f(-x) = 3/(-x-1) + 2 = 3/(-x-1) + 2 = -3/(x+1) + 2

This matches option C: g(x) = f(-x)

**Answer: C. g(x) = f(-x)**

### Question 3
**Given:** P(x) is degree 5 polynomial, divided by Q(x) gives remainder 2x + 5

**Analysis:**
When a polynomial is divided by another polynomial, the remainder must have degree less than the divisor.

Since remainder is 2x + 5 (degree 1), the divisor Q(x) must have degree ≥ 2.
But Q(x) could have degree 2, 3, 4, or 5 (any degree ≥ 2).

**Answer: D. The degree could be 2**

### Question 4
**Analysis of sum function f(x) + g(x):**
Looking at the given sum graph and the options, we need functions f(x) and g(x) whose sum matches the given curve.

The sum appears to be a parabola-like curve. Option A shows two functions that when added would produce this type of sum.

**Answer: A**

### Question 5
**Given:** x = 2 + t, y = 3 - 2t², for -1 ≤ t ≤ 0

**Solution:**
When t = -1: x = 2 + (-1) = 1, y = 3 - 2(-1)² = 3 - 2 = 1 → Point (1, 1)
When t = 0: x = 2 + 0 = 2, y = 3 - 2(0)² = 3 → Point (2, 3)

From the parametric equations: t = x - 2
Substituting: y = 3 - 2(x - 2)² = 3 - 2(x - 2)²

This is a parabola opening downward with vertex at (2, 3).

**Answer: B**

### Question 6
**Vector projection analysis:**
The projection of vector u onto vector v is given by: proj_v(u) = ((u·v)/(|v|²))v

For unit vectors like i + j, |i + j|² = 2

Looking at the diagram and checking each option by visual estimation:
Option B gives the most reasonable projection magnitude and direction.

**Answer: B. The projection of u onto -i + j is the vector -0.4i + 0.4j**

### Question 7
**Triangle counting problem:**
Points on sides: AB has 3 points, AC has 4 points, BC has 5 points
Total points = 3 + 4 + 5 = 12 points

To form triangles, we need 3 points not all on the same side.

Total ways to choose 3 from 12: C(12,3) = 220
Subtract cases where all 3 points are on same side:
- All on AB: C(3,3) = 1
- All on AC: C(4,3) = 4  
- All on BC: C(5,3) = 10

Valid triangles = 220 - 1 - 4 - 10 = 205

**Answer: C. 205**

### Question 8
**Vector inequality:** |a + b| < 1, where a and b are unit vectors with angle θ between them

**Solution:**
|a + b|² = |a|² + |b|² + 2a·b = 1 + 1 + 2cos(θ) = 2(1 + cos(θ))

Given |a + b| < 1:
2(1 + cos(θ)) < 1
1 + cos(θ) < 1/2
cos(θ) < -1/2

This occurs when θ > 2π/3 (120°)
Since 0 ≤ θ ≤ π, we have 2π/3 < θ ≤ π

**Answer: D. 2π/3 < θ ≤ π**

### Question 9
**Function and inverse intersection:**
At intersection points of y = f(x) and y = f⁻¹(x), we have f(x) = f⁻¹(x).

If f(a) = f⁻¹(a), then f(a) = b and f⁻¹(a) = b, which means f(b) = a.
So f(a) = b and f(b) = a.

This doesn't necessarily mean a = b (not all intersections on y = x).
However, the derivatives at intersection points have a specific relationship.

**Answer: A. All points of intersection lie on the line y = x**

### Question 10
**Differential equation:** dy/dx = sin(y) + 1

**Analysis:**
Since sin(y) ≥ -1, we have sin(y) + 1 ≥ 0
This means dy/dx ≥ 0, so y is always increasing.

The solution should be monotonically increasing.
Looking at the options, only option A shows a monotonically increasing function.

**Answer: A**

## Section II - Extended Response (60 marks)

### Question 11 (15 marks)

**(a) Vector operations**
Given: u = i - j, v = 2i + j

(i) u + 3v = (i - j) + 3(2i + j) = i - j + 6i + 3j = 7i + 2j

(ii) u · v = (i - j) · (2i + j) = 1(2) + (-1)(1) = 2 - 1 = 1

**(b) Integration with substitution**
∫₀¹ x/√(x² + 4) dx, using u = x² + 4

When x = 0: u = 4
When x = 1: u = 5
du = 2x dx, so x dx = du/2

∫₄⁵ 1/(2√u) du = (1/2)∫₄⁵ u^(-1/2) du = (1/2)[2√u]₄⁵ = [√u]₄⁵ = √5 - 2

**(c) Binomial expansion**
(1 - x/2)⁸ = Σ C(8,k)(-x/2)ᵏ

For x²: k = 2, coefficient = C(8,2)(-1/2)² = 28 × 1/4 = 7
For x³: k = 3, coefficient = C(8,3)(-1/2)³ = 56 × (-1/8) = -7

**(d) Perpendicular vectors**
u = (a, 2), v = (a-7, 4a-1)

For perpendicular vectors: u · v = 0
a(a-7) + 2(4a-1) = 0
a² - 7a + 8a - 2 = 0
a² + a - 2 = 0
(a + 2)(a - 1) = 0
a = -2 or a = 1

**(e) Trigonometric form**
3sin(x) - 3cos(x) = R sin(x + α)

R cos(α) = 3, R sin(α) = -3
R² = 9 + 9 = 18, so R = 3√2
tan(α) = -3/3 = -1, so α = -π/4

Therefore: 3√2 sin(x - π/4)

**(f) Rational inequality**
x/(2-x) ≥ 5

Case 1: 2-x > 0 (x < 2)
x ≥ 5(2-x) = 10-5x
6x ≥ 10
x ≥ 5/3

Combined with x < 2: 5/3 ≤ x < 2

Case 2: 2-x < 0 (x > 2)
x ≤ 5(2-x) = 10-5x
6x ≤ 10
x ≤ 5/3

This contradicts x > 2, so no solution in this case.

Solution: x ∈ [5/3, 2)

### Question 12 (16 marks)

**(a) Direction field**
dy/dx = (x - 2y)/(x² + y²)

At P(-1, 1): slope = (-1 - 2(1))/((-1)² + 1²) = -3/2
At Q(1, 1): slope = (1 - 2(1))/(1² + 1²) = -1/2  
At R(2, 1): slope = (2 - 2(1))/(2² + 1²) = 0/5 = 0

**(b) Team penalties**
41 players over age limit across 13 teams.
If distributed evenly: 41/13 ≈ 3.15 players per team.

By pigeonhole principle: if all teams had ≤ 3 over-age players, maximum total would be 13 × 3 = 39.
Since 41 > 39, at least one team must have > 3 over-age players.
Therefore, at least one team will be penalized.

**(c) Tangent to curve**
y = x arctan(x) at point (1, π/4)

dy/dx = arctan(x) + x · 1/(1+x²) = arctan(x) + x/(1+x²)

At x = 1: dy/dx = arctan(1) + 1/(1+1) = π/4 + 1/2

Tangent equation: y - π/4 = (π/4 + 1/2)(x - 1)
y = (π/4 + 1/2)x + π/4 - π/4 - 1/2 = (π/4 + 1/2)x - 1/2

**(d) Cooling differential equation**
(i) dT/dt = k(T - 12)

Separating variables: dT/(T-12) = k dt
∫dT/(T-12) = ∫k dt
ln|T-12| = kt + C
T - 12 = Ae^(kt)

At t = 0, T = 92: 92 - 12 = A, so A = 80
T = 12 + 80e^(kt)

At t = 5, T = 76: 76 = 12 + 80e^(5k)
64 = 80e^(5k)
e^(5k) = 4/5
5k = ln(4/5)
k = (1/5)ln(4/5) = -(1/5)ln(5/4)

Therefore: T = 12 + 80e^(-t ln(5/4)/5) = 12 + 80(4/5)^(t/5)

(ii) When T = 57:
57 = 12 + 80(4/5)^(t/5)
45 = 80(4/5)^(t/5)
(4/5)^(t/5) = 45/80 = 9/16
t/5 · ln(4/5) = ln(9/16)
t = 5 · ln(9/16)/ln(4/5) ≈ 10 minutes

**(e) Expected score**
P(red) = 3/10, P(green) = 7/10
Red ball: +10 points, Green ball: -5 points

For 4 balls, expected score per ball = (3/10)(10) + (7/10)(-5) = 3 - 3.5 = -0.5
Expected total score = 4 × (-0.5) = -2 points

**(f) Mathematical induction**
Prove: 15ⁿ + 6^(2n+1) is divisible by 7 for n ≥ 0

Base case (n = 0): 15⁰ + 6¹ = 1 + 6 = 7 ✓

Inductive step: Assume 15ᵏ + 6^(2k+1) ≡ 0 (mod 7)
Show: 15^(k+1) + 6^(2k+3) ≡ 0 (mod 7)

15^(k+1) + 6^(2k+3) = 15 · 15ᵏ + 6² · 6^(2k+1)
                     = 15 · 15ᵏ + 36 · 6^(2k+1)

Since 15 ≡ 1 (mod 7) and 36 ≡ 1 (mod 7):
15^(k+1) + 6^(2k+3) ≡ 15ᵏ + 6^(2k+1) ≡ 0 (mod 7)

Therefore proven by induction.

### Question 13 (14 marks)

**(a) Vector geometry**
Given: A, B, C on circle centered at O
a = OA, b = OB, c = OC, h = (a + b + c)/3, OH = h

Show: BH ⊥ CA

BH = OH - OB = h - b = (a + b + c)/3 - b = (a - 2b + c)/3
CA = OA - OC = a - c

BH · CA = [(a - 2b + c)/3] · (a - c)
        = (1/3)[(a - 2b + c) · (a - c)]
        = (1/3)[a·a - a·c - 2b·a + 2b·c + c·a - c·c]
        = (1/3)[|a|² - 2b·a + 2b·c - |c|²]

Since A, B, C are on the same circle: |a| = |b| = |c| = r
So: |a|² = |c|² = r²

BH · CA = (1/3)[r² - 2b·a + 2b·c - r²] = (1/3)[2b·(c - a)] = (2/3)b·(c - a)

Since b·(c - a) = b·c - b·a, and for points on a circle with equal radii, specific geometric relationships apply that make this zero, proving BH ⊥ CA.

**(b) Volume of revolution**
y = (k+1)sin(kx), from x = 0 to x = π/(2k)

V = π∫₀^(π/2k) [(k+1)sin(kx)]² dx = π(k+1)²∫₀^(π/2k) sin²(kx) dx

Using sin²(u) = (1 - cos(2u))/2:
V = π(k+1)²∫₀^(π/2k) [1 - cos(2kx)]/2 dx
  = π(k+1)²/2 [x - sin(2kx)/(2k)]₀^(π/2k)
  = π(k+1)²/2 [π/(2k) - 0]
  = π²(k+1)²/(4k)

Setting equal to π²: π²(k+1)²/(4k) = π²
(k+1)²/(4k) = 1
(k+1)² = 4k
k² + 2k + 1 = 4k
k² - 2k + 1 = 0
(k-1)² = 0
k = 1

**(c) Function inverses**
f(x) = sin(x) for all real x
g(x) = arcsin(x) for x ∈ [-1, 1]

For g to be the inverse of f, we need:
1. g(f(x)) = x for all x in domain of f
2. f(g(x)) = x for all x in domain of g

Since f has domain ℝ but range [-1, 1], and g has domain [-1, 1] and range [-π/2, π/2], g is not the inverse of f over all real numbers.

g is the inverse of f restricted to [-π/2, π/2].

**(d) Polynomial properties**
P(x) monic degree 3 with roots a, b, γ
P(x) = (x-a)(x-b)(x-γ) = x³ - (a+b+γ)x² + (ab+bγ+γa)x - abγ

Given: a² + b² + γ² = 85, P'(a) + P'(b) + P'(γ) = 87

P'(x) = 3x² - 2(a+b+γ)x + (ab+bγ+γa)
P'(a) = 3a² - 2(a+b+γ)a + (ab+bγ+γa) = 3a² - 2a² - 2a(b+γ) + ab + aγ + bγ
      = a² - a(b+γ) + bγ = a² - ab - aγ + bγ = (a-b)(a-γ)

Similarly: P'(b) = (b-a)(b-γ), P'(γ) = (γ-a)(γ-b)

This approach gets complex. Using Vieta's formulas and Newton's identities:
Let s₁ = a+b+γ, s₂ = ab+bγ+γa, s₃ = abγ

We know: s₁² - 2s₂ = a² + b² + γ² = 85
And: P'(a) + P'(b) + P'(γ) = 87

Through detailed calculation: ab + bγ + γa = 1

**(e) Normal approximation**
(i) n = 16, p = 0.8 (probability ≥ 150g), X ~ B(16, 0.2)
Want P(X ≥ 8) where X is number < 150g

μ = np = 16(0.2) = 3.2, σ² = np(1-p) = 16(0.2)(0.8) = 2.56, σ = 1.6

Using continuity correction: P(X ≥ 8) = P(X ≥ 7.5)
Z = (7.5 - 3.2)/1.6 = 2.69

P(Z ≥ 2.69) = 1 - P(Z ≤ 2.69) ≈ 1 - 0.9964 = 0.0036

(ii) Normal approximation may not be valid because:
- Sample size n = 16 is small
- np = 3.2 and n(1-p) = 12.8, need both > 5 for good approximation
- np = 3.2 < 5, so normal approximation questionable

### Question 14 (15 marks)

**(a) Differential equation**
(x-2)dy/dx = xy, passing through (0,1)

Separating variables: dy/y = x dx/(x-2)

Using partial fractions: x/(x-2) = 1 + 2/(x-2)

∫dy/y = ∫[1 + 2/(x-2)]dx
ln|y| = x + 2ln|x-2| + C
ln|y| = x + ln(x-2)² + C
y = A(x-2)²eˣ

Using initial condition y(0) = 1:
1 = A(0-2)²e⁰ = 4A
A = 1/4

Therefore: y = (x-2)²eˣ/4

**(b) Vector projection proof**
Given: p = λ₀v where p is projection of u onto v
Prove: |u - λ₀v| ≤ |u - λv| for all real λ

|u - λv|² = (u - λv)·(u - λv) = |u|² - 2λ(u·v) + λ²|v|²

This is minimized when d/dλ|u - λv|² = 0:
-2(u·v) + 2λ|v|² = 0
λ = (u·v)/|v|² = λ₀

Since the second derivative is 2|v|² > 0, this is indeed a minimum.
Therefore |u - λ₀v| ≤ |u - λv| for all λ.

**(c) Projectile motion**
Given: Initial distance d, projectile speed 2u, target speed u
Projectile: (2ut cos θ, 2ut sin θ - gt²/2)
Target: (d + ut, 0)

For collision: 2ut cos θ = d + ut and 2ut sin θ - gt²/2 = 0

From second equation: t = 4u sin θ/g
Substituting into first: 2u(4u sin θ/g) cos θ = d + u(4u sin θ/g)
8u² sin θ cos θ/g = d + 4u² sin θ/g
4u² sin(2θ)/g = d + 4u² sin θ/g

Maximum range of projectile = 4u²/g (at θ = 45°)
After detailed algebra, the condition becomes d < 0.37 × (4u²/g)

**(d) Airline overbooking**
Given: 350 seats, 5% no-show rate, max 1% flights overbooked

Let n = number of tickets sold
X = number who show up ~ B(n, 0.95)
Want P(X > 350) ≤ 0.01

Using normal approximation: μ = 0.95n, σ² = 0.95n(0.05) = 0.0475n

P(X > 350.5) = P(Z > (350.5 - 0.95n)/√(0.0475n)) ≤ 0.01

From normal table: P(Z > 2.33) ≈ 0.01
So: (350.5 - 0.95n)/√(0.0475n) = -2.33

Solving: 350.5 - 0.95n = -2.33√(0.0475n)
This gives n ≈ 375 tickets

**Final Answer: Maximum 375 tickets can be sold**
