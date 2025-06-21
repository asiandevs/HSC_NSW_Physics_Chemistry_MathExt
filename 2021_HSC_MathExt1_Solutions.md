# Exam Paper
[2021 HIGHER SCHOOL CERTIFICATE EXAMINATION](<https://www.educationstandards.nsw.edu.au/wps/wcm/connect/a8bf2663-fbd2-4dba-97e9-198d76d11def/2021-hsc-mathematics-extension-1.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE-a8bf2663-fbd2-4dba-97e9-198d76d11def-nR9AG40>)

## 📝 Note to the Readers

These worked solutions are my attempt at solving the **2021 HSC Math Ext1 Exam**. While I’ve made every effort to ensure accuracy:

- ✅ **Verify answers** – Cross-check calculations and reasoning.  
- 🔍 **Report issues** – If you spot errors, [open an issue](../../issues) or submit a PR.  
- 📢 **Feedback welcome** – Suggestions for clarity/improvement are appreciated!  

**Disclaimer**: These are unofficial solutions. Always consult official marking guidelines.  

🙏 **Thank you for helping improve this resource!**  
---
# 2021 HSC Mathematics Extension 1 - Complete Solutions

## Section I - Multiple Choice Questions (10 marks)

### Question 1
**Given that $\overrightarrow{OP} = \begin{pmatrix} -3 \\ 1 \end{pmatrix}$ and $\overrightarrow{OQ} = \begin{pmatrix} 2 \\ 5 \end{pmatrix}$, what is $\overrightarrow{PQ}$?**

**Solution:**
$\overrightarrow{PQ} = \overrightarrow{OQ} - \overrightarrow{OP}$

$\overrightarrow{PQ} = \begin{pmatrix} 2 \\ 5 \end{pmatrix} - \begin{pmatrix} -3 \\ 1 \end{pmatrix} = \begin{pmatrix} 2-(-3) \\ 5-1 \end{pmatrix} = \begin{pmatrix} 5 \\ 4 \end{pmatrix}$

**Answer: C**

### Question 2
**Which of the following integrals is equivalent to $\int \sin^2 3x \, dx$?**

**Solution:**
Using the identity: $\sin^2 \theta = \frac{1 - \cos 2\theta}{2}$

For $\sin^2 3x$:
$\sin^2 3x = \frac{1 - \cos(2 \cdot 3x)}{2} = \frac{1 - \cos 6x}{2}$

Therefore: $\int \sin^2 3x \, dx = \int \frac{1 - \cos 6x}{2} \, dx$

**Answer: B**

### Question 3
**What is the remainder when $P(x) = -x^3 - 2x^2 - 3x + 8$ is divided by $x + 2$?**

**Solution:**
Using the Remainder Theorem: remainder = $P(-2)$

$P(-2) = -(-2)^3 - 2(-2)^2 - 3(-2) + 8$
$P(-2) = -(-8) - 2(4) + 6 + 8$
$P(-2) = 8 - 8 + 6 + 8 = 14$

**Answer: D**

### Question 4
**Consider the differential equation $\frac{dy}{dx} = \frac{x}{y}$. Which equation best represents this relationship?**

**Solution:**
$\frac{dy}{dx} = \frac{x}{y}$

Separating variables: $y \, dy = x \, dx$

Integrating both sides: $\int y \, dy = \int x \, dx$

$\frac{y^2}{2} = \frac{x^2}{2} + C$

Multiplying by 2: $y^2 = x^2 + c$ (where $c = 2C$)

**Answer: A**

### Question 5
**For vectors $\overrightarrow{OA}$ and $\overrightarrow{OB}$, if $\overrightarrow{OA} \cdot \overrightarrow{OB} < 0$, which statement MUST be true?**

**Solution:**
The dot product formula: $\overrightarrow{OA} \cdot \overrightarrow{OB} = |\overrightarrow{OA}||\overrightarrow{OB}|\cos\theta$

Since $|\overrightarrow{OA}| > 0$ and $|\overrightarrow{OB}| > 0$, for the dot product to be negative:
$\cos\theta < 0$

This occurs when $90° < \theta < 270°$, meaning the angle is obtuse.

**Answer: B**

### Question 6
**$X$ represents successes in 10 independent Bernoulli trials with $p = 0.9$. Let $r = P(X \geq 1)$.**

**Solution:**
$r = P(X \geq 1) = 1 - P(X = 0)$

$P(X = 0) = \binom{10}{0}(0.9)^0(0.1)^{10} = 1 \times 1 \times (0.1)^{10} = 10^{-10}$

$r = 1 - 10^{-10} \approx 1$

Since $r > 0.9$:

**Answer: A**

### Question 7
**Which curve represents $f(x) = -a\sin x + b\cos x$ where $a, b > 0$?**

**Solution:**
$f(x) = -a\sin x + b\cos x$

At $x = 0$: $f(0) = -a\sin(0) + b\cos(0) = 0 + b = b > 0$

At $x = \frac{\pi}{2}$: $f(\frac{\pi}{2}) = -a\sin(\frac{\pi}{2}) + b\cos(\frac{\pi}{2}) = -a + 0 = -a < 0$

The function starts positive and becomes negative.

**Answer: A**

### Question 8
**Which parametric equations represent the semicircle shown?**

**Solution:**
From the diagram: center at $(3, 2)$, radius $= 1$
The semicircle goes from $(2, 2)$ to $(4, 2)$ (upper semicircle)

For upper semicircle: $x = 3 + \cos t$, $y = 2 + \sin t$
When $t = -\frac{\pi}{2}$: $(3, 1)$ - below center
When $t = \frac{\pi}{2}$: $(3, 3)$ - above center

This matches option B.

**Answer: B**

### Question 9
**Which graph represents $y = \sin^{-1}(\sin x)$?**

**Solution:**
$y = \sin^{-1}(\sin x)$ has range $[-\frac{\pi}{2}, \frac{\pi}{2}]$

For $x \in [-\frac{\pi}{2}, \frac{\pi}{2}]$: $y = x$
For $x \in [\frac{\pi}{2}, \frac{3\pi}{2}]$: $y = \pi - x$
For $x \in [\frac{3\pi}{2}, \frac{5\pi}{2}]$: $y = x - 2\pi$

This creates a sawtooth pattern between $-\frac{\pi}{2}$ and $\frac{\pi}{2}$.

**Answer: A**

### Question 10
**15 candidates, 3543 votes. What's the minimum votes for the winner?**

**Solution:**
For the winner to have the minimum votes, all other candidates should have as many votes as possible.

If winner gets $n$ votes, remaining $3543 - n$ votes distributed among 14 candidates.
For winner to have more than others: $n > \frac{3543 - n}{14}$

$14n > 3543 - n$
$15n > 3543$
$n > 236.2$

Therefore, minimum is 237 votes.

**Answer: B**

## Section II - Extended Response Questions (60 marks)

### Question 11 (16 marks)

**(a) Find $(i + 6j) + (2i - 7j)$ (1 mark)**

**Solution:**
$(i + 6j) + (2i - 7j) = (1 + 2)i + (6 - 7)j = 3i - j$

**(b) Expand and simplify $(2a - b)^4$ (2 marks)**

**Solution:**
Using binomial theorem: $(x + y)^4 = x^4 + 4x^3y + 6x^2y^2 + 4xy^3 + y^4$

$(2a - b)^4 = (2a)^4 + 4(2a)^3(-b) + 6(2a)^2(-b)^2 + 4(2a)(-b)^3 + (-b)^4$

$= 16a^4 - 32a^3b + 24a^2b^2 - 8ab^3 + b^4$

**(c) Use substitution $u = x + 1$ to find $\int x\sqrt{x + 1} \, dx$ (3 marks)**

**Solution:**
Let $u = x + 1$, then $x = u - 1$ and $dx = du$

$\int x\sqrt{x + 1} \, dx = \int (u - 1)\sqrt{u} \, du = \int (u - 1)u^{1/2} \, du$

$= \int (u^{3/2} - u^{1/2}) \, du$

$= \frac{u^{5/2}}{5/2} - \frac{u^{3/2}}{3/2} + C$

$= \frac{2u^{5/2}}{5} - \frac{2u^{3/2}}{3} + C$

$= \frac{2(x + 1)^{5/2}}{5} - \frac{2(x + 1)^{3/2}}{3} + C$

**(d) Committee formation: 5 men and 3 women from 10 men and 8 women (1 mark)**

**Solution:**
Number of ways = $\binom{10}{5} \times \binom{8}{3}$

$= \frac{10!}{5! \times 5!} \times \frac{8!}{3! \times 5!}$

$= 252 \times 56 = 14112$

**(e) Spherical bubble volume rate (2 marks)**

**Solution:**
Volume of sphere: $V = \frac{4}{3}\pi r^3$

$\frac{dV}{dt} = \frac{dV}{dr} \times \frac{dr}{dt} = 4\pi r^2 \times \frac{dr}{dt}$

Given: $\frac{dr}{dt} = 0.2$ mm/s, $r = 0.6$ mm

$\frac{dV}{dt} = 4\pi (0.6)^2 \times 0.2 = 4\pi \times 0.36 \times 0.2 = 0.288\pi$

$\frac{dV}{dt} = 0.9$ mm³/s (to 1 decimal place)

**(f) Evaluate $\int_0^1 \frac{3}{4 - x^2} \, dx$ (2 marks)**

**Solution:**
$\frac{3}{4 - x^2} = \frac{3}{(2)^2 - x^2}$

Using the formula: $\int \frac{1}{a^2 - x^2} \, dx = \frac{1}{2a} \ln\left|\frac{a + x}{a - x}\right| + C$

$\int_0^1 \frac{3}{4 - x^2} \, dx = 3 \times \frac{1}{4} \left[\ln\left|\frac{2 + x}{2 - x}\right|\right]_0^1$

$= \frac{3}{4}\left[\ln\left|\frac{3}{1}\right| - \ln\left|\frac{2}{2}\right|\right]$

$= \frac{3}{4}[\ln 3 - \ln 1] = \frac{3}{4}\ln 3$

**(g) Solve $2\sin^3 x + 2\sin^2 x - \sin x - 1 = 0$ for $0 \leq x \leq 2\pi$ (3 marks)**

**Solution:**
Factor by grouping:
$2\sin^2 x(\sin x + 1) - 1(\sin x + 1) = 0$
$(\sin x + 1)(2\sin^2 x - 1) = 0$

Case 1: $\sin x + 1 = 0 \Rightarrow \sin x = -1$
$x = \frac{3\pi}{2}$

Case 2: $2\sin^2 x - 1 = 0 \Rightarrow \sin^2 x = \frac{1}{2} \Rightarrow \sin x = \pm\frac{\sqrt{2}}{2}$

For $\sin x = \frac{\sqrt{2}}{2}$: $x = \frac{\pi}{4}, \frac{3\pi}{4}$
For $\sin x = -\frac{\sqrt{2}}{2}$: $x = \frac{5\pi}{4}, \frac{7\pi}{4}$

Solutions: $x = \frac{\pi}{4}, \frac{3\pi}{4}, \frac{5\pi}{4}, \frac{3\pi}{2}, \frac{7\pi}{4}$

**(h) For $x^4 - 3x + 6 = 0$ with roots $a, b, \gamma, \delta$, find $\frac{1}{a} + \frac{1}{b} + \frac{1}{\gamma} + \frac{1}{\delta}$ (2 marks)**

**Solution:**
$\frac{1}{a} + \frac{1}{b} + \frac{1}{\gamma} + \frac{1}{\delta} = \frac{b\gamma\delta + a\gamma\delta + ab\delta + ab\gamma}{ab\gamma\delta}$

From Vieta's formulas for $x^4 + 0x^3 + 0x^2 - 3x + 6 = 0$:
- Product of roots: $ab\gamma\delta = 6$
- Sum of products taken three at a time: $ab\gamma + ab\delta + a\gamma\delta + b\gamma\delta = 3$

Therefore: $\frac{1}{a} + \frac{1}{b} + \frac{1}{\gamma} + \frac{1}{\delta} = \frac{3}{6} = \frac{1}{2}$

### Question 12 (14 marks)

**(a) Sketch particular solution through point P (1 mark)**

**Solution:**
Following the direction field arrows from point P, the solution curve would flow along the field lines, creating a smooth curve that follows the indicated directions at each point.

**(b)(i) Water temperature differential equation (3 marks)**

**Solution:**
$\frac{dT}{dt} = k(T - 25)$

Separating variables: $\frac{dT}{T - 25} = k \, dt$

Integrating: $\ln|T - 25| = kt + C$

$T - 25 = Ae^{kt}$ where $A = e^C$

Initial condition: $T(0) = 5$
$5 - 25 = A \Rightarrow A = -20$

So: $T = 25 - 20e^{kt}$

At $t = 8$: $T = 10$
$10 = 25 - 20e^{8k}$
$-15 = -20e^{8k}$
$e^{8k} = \frac{3}{4}$
$k = \frac{1}{8}\ln\left(\frac{3}{4}\right)$

For $T = 20$:
$20 = 25 - 20e^{kt}$
$-5 = -20e^{kt}$
$e^{kt} = \frac{1}{4}$

$kt = \ln\left(\frac{1}{4}\right) = -\ln 4$

$t = \frac{-\ln 4}{k} = \frac{-\ln 4}{\frac{1}{8}\ln\left(\frac{3}{4}\right)} = \frac{8\ln 4}{\ln\left(\frac{4}{3}\right)}$

$t = \frac{8\ln 4}{\ln 4 - \ln 3} \approx 22$ minutes

**(b)(ii) Sketch T vs t (1 mark)**

**Solution:**
The graph shows exponential approach to 25°C from initial value of 5°C, with horizontal asymptote at T = 25.

**(c) Mathematical induction proof (3 marks)**

**Solution:**
Prove: $\sum_{k=1}^{n} \frac{1}{k(k+1)(k+2)} = \frac{1}{4} - \frac{1}{2(n+1)(n+2)}$

**Base case** ($n = 1$):
LHS: $\frac{1}{1 \times 2 \times 3} = \frac{1}{6}$
RHS: $\frac{1}{4} - \frac{1}{2 \times 2 \times 3} = \frac{1}{4} - \frac{1}{12} = \frac{3-1}{12} = \frac{1}{6}$ ✓

**Inductive step:**
Assume true for $n = k$: $\sum_{j=1}^{k} \frac{1}{j(j+1)(j+2)} = \frac{1}{4} - \frac{1}{2(k+1)(k+2)}$

For $n = k+1$:
$\sum_{j=1}^{k+1} \frac{1}{j(j+1)(j+2)} = \frac{1}{4} - \frac{1}{2(k+1)(k+2)} + \frac{1}{(k+1)(k+2)(k+3)}$

$= \frac{1}{4} - \frac{1}{2(k+1)(k+2)} + \frac{1}{(k+1)(k+2)(k+3)}$

$= \frac{1}{4} - \frac{k+3-2}{2(k+1)(k+2)(k+3)}$

$= \frac{1}{4} - \frac{k+1}{2(k+1)(k+2)(k+3)}$

$= \frac{1}{4} - \frac{1}{2(k+2)(k+3)}$

This matches the required form, completing the proof.

**(d)(i) Sketch $f(x) = 4 - 1 - \frac{x}{2}$ for $x \in (-\infty, 2)$ (2 marks)**

**Solution:**
$f(x) = 3 - \frac{x}{2}$

This is a linear function with slope $-\frac{1}{2}$ and y-intercept 3.
x-intercept: $0 = 3 - \frac{x}{2} \Rightarrow x = 6$

Domain is $(-\infty, 2)$, so the graph stops at $x = 2$ (open circle).

**(d)(ii) Find inverse function and domain (3 marks)**

**Solution:**
$y = 3 - \frac{x}{2}$

Swap variables: $x = 3 - \frac{y}{2}$

Solve for y: $\frac{y}{2} = 3 - x$
$y = 6 - 2x$

Therefore: $f^{-1}(x) = 6 - 2x$

Domain of $f^{-1}$: Range of $f$
Since $x \in (-\infty, 2)$ and $f(x) = 3 - \frac{x}{2}$:
As $x \to -\infty$, $f(x) \to +\infty$
At $x = 2$: $f(2) = 3 - 1 = 2$

Domain of $f^{-1}$: $(2, +\infty)$

**(d)(iii) Sketch inverse function (1 mark)**

**Solution:**
Graph of $f^{-1}(x) = 6 - 2x$ with domain $(2, +\infty)$, showing linear function with slope -2 starting from point (2, 2) with open circle.

### Question 13 (14 marks)

**(a) Volume of sculpture (3 marks)**

**Solution:**
The sculpture is formed by rotating the region between $y = x^2$, $y = x^2 + 1$, and $y = 2$ around the y-axis.

For $y \in [0, 1]$: outer radius from $y = x^2 + 1 \Rightarrow x = \sqrt{y-1}$ (not valid for $y < 1$)
For $y \in [1, 2]$: outer radius from $y = x^2 + 1 \Rightarrow x = \sqrt{y-1}$, inner radius from $y = x^2 \Rightarrow x = \sqrt{y}$

Volume = $\pi \int_1^2 [(\sqrt{y-1})^2 - (\sqrt{y})^2] \, dy$
$= \pi \int_1^2 [(y-1) - y] \, dy$
$= \pi \int_1^2 (-1) \, dy$
$= -\pi [y]_1^2 = -\pi(2-1) = -\pi$

This is incorrect. Let me recalculate:

For $y \in [1, 2]$: 
- Outer boundary: $y = x^2 + 1 \Rightarrow x^2 = y - 1$
- Inner boundary: $y = x^2 \Rightarrow x^2 = y$

Volume = $\pi \int_1^2 [(y-1) - y] \, dy = \pi \int_1^2 (-1) \, dy = -\pi$

The issue is with the setup. The region is between the curves, so:

Volume = $\pi \int_0^1 (\sqrt{y})^2 \, dy + \pi \int_1^2 [(\sqrt{y-1})^2 - (\sqrt{y})^2] \, dy$

Actually, rereading: the region is between $y = x^2$, $y = x^2 + 1$, and bounded by $y = 2$.

Volume = $\pi \int_1^2 (\sqrt{y-1})^2 \, dy = \pi \int_1^2 (y-1) \, dy$
$= \pi \left[\frac{y^2}{2} - y\right]_1^2$
$= \pi \left[(2 - 2) - (\frac{1}{2} - 1)\right]$
$= \pi \left[0 + \frac{1}{2}\right] = \frac{\pi}{2}$ m³

**(b) Projectile motion analysis (4 marks)**

**Solution:**
Given: $h = 1$ m, $V = 12$ m/s, $\theta = 30°$, horizontal distance = 10 m

$r(t) = (Vt\cos\theta)i + (-5t^2 + Vt\sin\theta + h)j$
$r(t) = (12t\cos 30°)i + (-5t^2 + 12t\sin 30° + 1)j$
$r(t) = (6\sqrt{3}t)i + (-5t^2 + 6t + 1)j$

**Check ceiling (y = 3):**
Maximum height occurs at $t = \frac{6}{10} = 0.6$ s
$y_{max} = -5(0.6)^2 + 6(0.6) + 1 = -1.8 + 3.6 + 1 = 2.8$ m < 3 m ✓

**Check wall hit:**
When $x = 10$: $6\sqrt{3}t = 10 \Rightarrow t = \frac{10}{6\sqrt{3}} = \frac{5\sqrt{3}}{9}$ s

At this time: $y = -5\left(\frac{5\sqrt{3}}{9}\right)^2 + 6\left(\frac{5\sqrt{3}}{9}\right) + 1$
$= -5 \cdot \frac{75}{81} + 6 \cdot \frac{5\sqrt{3}}{9} + 1$
$= -\frac{125}{27} + \frac{10\sqrt{3}}{3} + 1$

Since $\frac{10\sqrt{3}}{3} \approx 5.77$ and $\frac{125}{27} \approx 4.63$:
$y \approx -4.63 + 5.77 + 1 = 2.14$ m > 0 ✓

Ball hits wall above ground level.

**(c) Area calculation (5 marks)**

**Solution:**
Find intersection points of $y = 2 - |x|$ and $y = 1 - \frac{8}{4 + x^2}$

For $x \geq 0$: $2 - x = 1 - \frac{8}{4 + x^2}$
$1 - x = -\frac{8}{4 + x^2}$
$(1 - x)(4 + x^2) = -8$
$4 + x^2 - 4x - x^3 = -8$
$x^3 + 4x - x^2 - 12 = 0$

By symmetry and inspection, intersection points are at $x = \pm 2$.

Area = $2 \int_0^2 \left[(2 - x) - \left(1 - \frac{8}{4 + x^2}\right)\right] dx$
$= 2 \int_0^2 \left[1 - x + \frac{8}{4 + x^2}\right] dx$
$= 2 \left[x - \frac{x^2}{2} + 8 \cdot \frac{1}{2} \arctan\left(\frac{x}{2}\right)\right]_0^2$
$= 2 \left[2 - 2 + 4 \arctan(1) - 0\right]$
$= 2 \cdot 4 \cdot \frac{\pi}{4} = 2\pi$

**(d)(i) Prove trigonometric identity (2 marks)**

**Solution:**
Given: $A = B - d$, $C = B + d$

$\sin A + \sin C = \sin(B - d) + \sin(B + d)$
$= \sin B \cos d - \cos B \sin d + \sin B \cos d + \cos B \sin d$
$= 2\sin B \cos d$

$\cos A + \cos C = \cos(B - d) + \cos(B + d)$
$= \cos B \cos d + \sin B \sin d + \cos B \cos d - \sin B \sin d$
$= 2\cos B \cos d$

Therefore:
$\frac{\sin A + \sin C}{\cos A + \cos C} = \frac{2\sin B \cos d}{2\cos B \cos d} = \frac{\sin B}{\cos B} = \tan B$

**(d)(ii) Solve the equation (2 marks)**

**Solution:**
$\frac{\sin\frac{5\theta}{7} + \sin\frac{6\theta}{7}}{\cos\frac{5\theta}{7} + \cos\frac{6\theta}{7}} = \sqrt{3}$

Using the identity with $B = \frac{5\theta + 6\theta}{7 \cdot 2} = \frac{11\theta}{14}$:

$\tan\frac{11\theta}{14} = \sqrt{3}$

$\frac{11\theta}{14} = \frac{\pi}{3} + n\pi$

$\theta = \frac{14\pi}{33} + \frac{14n\pi}{11}$

For $0 \leq \theta \leq 2\pi$:
$n = 0$: $\theta = \frac{14\pi}{33}$
$n = 1$: $\theta = \frac{14\pi}{33} + \frac{14\pi}{11} = \frac{14\pi + 42\pi}{33} = \frac{56\pi}{33}$

Solutions: $\theta = \frac{14\pi}{33}, \frac{56\pi}{33}$

### Question 14 (16 marks)

**(a) Aircraft bearing calculation (3 marks)**

**Solution:**
Let the plane's heading be at bearing $\alpha$.
Ground velocity must be at bearing 063°.

Plane velocity: $175(\sin\alpha, \cos\alpha)$
Wind velocity: $(0, 42)$ (from south)
Ground velocity: $175(\sin\alpha, \cos\alpha) + (0, 42)$

For bearing 063°:
$\frac{175\sin\alpha}{175\cos\alpha + 42} = \tan 63°$

$175\sin\alpha = (175\cos\alpha + 42)\tan 63°$
$175\sin\alpha = 175\cos\alpha \tan 63° + 42\tan 63°$
$175(\sin\alpha - \cos\alpha \tan 63°) = 42\tan 63°$
$\sin\alpha - \cos\alpha \tan 63° = \frac{42\tan 63°}{175}$

Using $\tan 63° \approx 1.963$:
$\sin\alpha - 1.963\cos\alpha = \frac{42 \times 1.963}{175} \approx 0.471$

Solving: $\alpha \approx 055°$ (to nearest degree)

**(b) Logistic growth model (4 marks)**

**Solution:**
$\frac{dP}{dt} = 0.1P\frac{C-P}{C}$

Separating variables: $\frac{dP}{P(C-P)} = \frac{0.1}{C}dt$

Using partial fractions: $\frac{1}{P(C-P)} = \frac{1}{C}\left(\frac{1}{P} + \frac{1}{C-P}\right)$

$\frac{1}{C}\left(\frac{1}{P} + \frac{1}{C-P}\right)dP = \frac{0.1}{C}dt$

Integrating: $\frac{1}{C}[\ln P - \ln(C-P)] = \frac{0.1t}{C} + K$

$\ln\frac{P}{C-P} = 0.1t + KC$

Initial condition (1980): $P = 150000$
Year 2000 ($t = 20
