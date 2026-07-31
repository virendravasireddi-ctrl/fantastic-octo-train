# 01 · Number System, HCF & LCM, Powers & Roots, Orders of Magnitude

[Index](README.md) · [Next: Ratio, Percentage, Profit & Interest →](02-Ratio-Proportion-Percentage-Profit-and-Interest.md)

**Syllabus phrases covered:** *"number system and order of magnitude"*, *"power and exponent, square, square root, cube root, H.C.F. and L.C.M."*

**PYQ signal:** APPSC sets this block as **short, formula-free, one-step questions** — divisibility, unit digit, remainder, the largest/smallest number of a kind, bells-ringing-together LCM problems, and a square-root/cube-root recall. High return per minute; do it in Pass 1.

---

## 1. The number tree

```
                       Numbers
                          |
        ┌─────────────────┴─────────────────┐
      Real                             Imaginary (√−1)
        |
  ┌─────┴─────┐
Rational   Irrational (√2, π, e — non-terminating, non-recurring)
  |
  ├── Integers ── Negative | Zero | Positive
  |                                    |
  |                              Natural numbers (1,2,3…)
  |                                    ├── Prime (exactly 2 factors)
  |                                    ├── Composite (>2 factors)
  |                                    └── 1 (neither prime nor composite)
  └── Fractions (p/q, q≠0)
```

**Definitions examiners exploit:**

| Term | Exact meaning | The trap |
|---|---|---|
| **Whole numbers** | 0, 1, 2, 3… | **Includes 0**; natural numbers do not |
| **Prime** | exactly two distinct factors | **1 is not prime; 2 is the only even prime** |
| **Co-prime** | HCF = 1 | Co-primes **need not be prime** (8 & 9 are co-prime) |
| **Rational** | expressible as p/q | Terminating **or** recurring decimals are both rational |
| **Even/odd** | divisible / not divisible by 2 | **0 is even** |
| **Composite** | more than two factors | **4 is the smallest composite**; 1 is neither |

- **Primes below 100 (25 of them)** — memorise: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97.
- **Test for primality ⚡:** to check if *n* is prime, test divisibility by primes **up to √n only**. 191? √191 ≈ 13.8 → test 2, 3, 5, 7, 11, 13 → none divide → prime.

---

## 2. Divisibility rules ⭐ (memorise all)

| By | Rule |
|---|---|
| **2** | last digit even |
| **3** | digit sum divisible by 3 |
| **4** | **last two digits** divisible by 4 |
| **5** | ends in 0 or 5 |
| **6** | divisible by 2 **and** 3 |
| **7** | double the last digit, subtract from the rest; repeat (1073 → 107 − 6 = 101 → no) |
| **8** | **last three digits** divisible by 8 |
| **9** | digit sum divisible by 9 |
| **10** | ends in 0 |
| **11** | (sum of odd-place digits) − (sum of even-place digits) = 0 or multiple of 11 |
| **12** | divisible by 3 **and** 4 |
| **25** | last two digits divisible by 25 |

⚡ **Composite-divisor rule:** to test divisibility by a composite number, split it into **co-prime** factors. For 36 use 4 × 9 (co-prime) ✔, **not** 6 × 6 ✘.

---

## 3. Factors, unit digits, remainders

### 3.1 Number of factors ⭐
If N = a^p · b^q · c^r (a, b, c prime), then:

- **Number of factors = (p+1)(q+1)(r+1)**
- **Sum of factors** = [(a^(p+1)−1)/(a−1)] × [(b^(q+1)−1)/(b−1)] × …
- **Number of ways to write N as a product of two factors** = ½ × (number of factors); if N is a perfect square, = ½ × (factors + 1).

*Example:* 360 = 2³·3²·5¹ → factors = 4·3·2 = **24**.

### 3.2 Unit digit ⚡ (a guaranteed 60-second mark)

The unit digit of a^n **cycles with period 4**:

| Unit digit of base | Cycle | Period |
|---|---|---|
| 0, 1, 5, 6 | always itself | 1 |
| 4 | 4, 6 | 2 |
| 9 | 9, 1 | 2 |
| 2 | 2, 4, 8, 6 | 4 |
| 3 | 3, 9, 7, 1 | 4 |
| 7 | 7, 9, 3, 1 | 4 |
| 8 | 8, 4, 2, 6 | 4 |

**Method:** divide the exponent by 4; take the remainder *r*; if r = 0 use the **4th** term of the cycle.
*Example:* unit digit of 7^102 → 102 ÷ 4 leaves 2 → 2nd term of (7,9,3,1) = **9**.

### 3.3 Remainders

- **Basic:** Dividend = Divisor × Quotient + Remainder.
- **Remainder of a product = product of remainders** (then reduce). Remainder of (17 × 23) ÷ 5 = (2 × 3) ÷ 5 → **1**.
- **Negative-remainder trick ⚡:** remainder of 99^99 ÷ 100 → 99 ≡ −1 → (−1)^99 = −1 ≡ **99**.
- **Fermat's little theorem** (rarely needed): if p is prime and a not divisible by p, a^(p−1) ≡ 1 (mod p).
- **Successive division** — read carefully: "a number when successively divided by 3 and 5 leaves remainders 1 and 2" means the *quotient* of the first division is fed into the second. Work **backwards**: take the last quotient as 1 → 1 × 5 + 2 = 7 → 7 × 3 + 1 = **22**.

### 3.4 Standard "find the number" templates ⭐

| Question | Method |
|---|---|
| Greatest number that divides x, y, z **exactly** | **HCF (x, y, z)** |
| Greatest number that divides x, y, z leaving **the same remainder r** | HCF of (x−r), (y−r), (z−r) |
| Greatest number that divides x, y, z leaving **remainders a, b, c** | HCF of (x−a), (y−b), (z−c) |
| Greatest number that divides x, y, z leaving the **same unknown remainder** | **HCF of the differences**: (y−x), (z−y), (z−x) |
| Least number **exactly divisible** by x, y, z | **LCM (x, y, z)** |
| Least number leaving remainder **r in each case** | **LCM + r** |
| Least number leaving remainders a, b, c where (x−a) = (y−b) = (z−c) = k | **LCM − k** |
| Greatest n-digit number divisible by x, y, z | LCM → divide the greatest n-digit number by it → **subtract the remainder** |

---

## 4. HCF and LCM ⭐⭐

- **HCF (GCD)** = largest number dividing all; **LCM** = smallest number divisible by all.
- **Prime-factorisation method:** HCF = product of **common primes with the lowest** powers; LCM = product of **all primes with the highest** powers.
- **Division (Euclid) method** for HCF of two big numbers: divide larger by smaller, then divisor by remainder, repeat; the last non-zero remainder is the HCF.

### 4.1 The formulae to hold

| Result | Statement |
|---|---|
| **Product rule** | **HCF × LCM = product of the two numbers** — *only true for two numbers*, never for three ⚠️ |
| **Fractions** | **HCF of fractions = HCF(numerators) / LCM(denominators)**; **LCM of fractions = LCM(numerators) / HCF(denominators)** |
| **Co-prime pair** | HCF = 1, so LCM = product |
| **If numbers are a·x and a·y with x, y co-prime** | HCF = a, LCM = a·x·y |
| **Decimals** | equalise decimal places, treat as integers, replace the decimal point at the end |

### 4.2 The classic word problems

- **Bells / lights / traffic signals ringing together:** they coincide every **LCM** seconds. In T seconds they coincide **T ÷ LCM** times *after the start* — add 1 if the start moment counts. ⚠️ This "+1" is the commonest silly loss.
- **Largest tile / measuring rod / equal-length pieces / maximum students in a group:** **HCF**.
- **Racetrack / circular track meeting at start point:** LCM of individual lap times.
- **Least number of a kind (soldiers arranged in rows, apples in baskets):** LCM ± adjustment.

> ⚡ **Instant read:** the words **"greatest / largest / maximum / exactly divides"** → **HCF**. The words **"least / smallest / together again / minimum number that is divisible"** → **LCM**. This one line answers most APPSC questions in this block without any calculation beyond the factorisation.

---

## 5. Powers, exponents, squares and roots

### 5.1 Laws of exponents

a^m · a^n = a^(m+n) · a^m ÷ a^n = a^(m−n) · (a^m)^n = a^(mn) · (ab)^n = a^n b^n · a^0 = 1 (a ≠ 0) · a^(−n) = 1/a^n · a^(1/n) = ⁿ√a

**Comparing powers ⚡:** make the **exponents equal** (not the bases) and compare bases — e.g. compare 2^40 and 3^30: 2^40 = (2^4)^10 = 16^10, 3^30 = (3^3)^10 = 27^10 → **3^30 is bigger**.

### 5.2 Squares — memorise 1–30

| n | n² | n | n² | n | n² |
|---|---|---|---|---|---|
| 11 | 121 | 18 | 324 | 25 | 625 |
| 12 | 144 | 19 | 361 | 26 | 676 |
| 13 | 169 | 20 | 400 | 27 | 729 |
| 14 | 196 | 21 | 441 | 28 | 784 |
| 15 | 225 | 22 | 484 | 29 | 841 |
| 16 | 256 | 23 | 529 | 30 | 900 |
| 17 | 289 | 24 | 576 | 31 | 961 |

**Cubes 1–15:** 1, 8, 27, 64, 125, 216, 343, 512, 729, 1000, 1331, 1728, 2197, 2744, 3375.

**Squaring shortcuts ⚡**
- **Numbers ending in 5:** (n5)² = n(n+1) followed by 25. 85² → 8×9 = 72 → **7225**.
- **Near 100:** 96² → (96 − 4) | 4² → **9216**. 103² → (103 + 3) | 3² → **10609**.
- **Algebraic:** (a ± b)² = a² ± 2ab + b²; a² − b² = (a+b)(a−b) — use for 63² − 37² = 100 × 26 = **2600**.

**Properties that kill options instantly ⚠️**
- A perfect square **never ends in 2, 3, 7 or 8**, and never has an odd number of trailing zeros.
- Digit sum of a perfect square reduces to **1, 4, 7 or 9**.
- A perfect square has an **odd** number of factors; every other number has an even number.

### 5.3 Square roots and cube roots

- **Square root by unit digit ⚡** (for perfect squares of ≤4 digits): the unit digit of the root is fixed by the unit digit of the number (1→1 or 9; 4→2 or 8; 5→5; 6→4 or 6; 9→3 or 7; 0→0). Then bracket the remaining digits between known squares.
  *Example:* √4489 → ends in 9 → root ends in 3 or 7; 4489 lies between 60²=3600 and 70²=4900 → root is 6_ → **67**.
- **Cube root by unit digit ⚡:** cube-unit-digit map is one-to-one — 1→1, 8→2, 7→3, 4→4, 5→5, 6→6, 3→7, 2→8, 9→9, 0→0. For √³ 19683: last digit 3 → root ends in 7; strip last 3 digits → 19 lies between 2³=8 and 3³=27 → tens digit 2 → **27**.
- **Surds:** rationalise by multiplying with the conjugate — 1/(√5 − √3) × (√5 + √3)/(√5 + √3) = (√5 + √3)/2.
- **Nested radicals:** √(a√(a√(a…))) with n radicals = a^((2ⁿ−1)/2ⁿ); the infinite case √(a + √(a + …)) solves x² = a + x.

---

## 6. Order of magnitude and approximation ⭐

The syllabus phrase **"order of magnitude"** means: judging *the size class* of a number and comparing quantities without exact computation. APPSC tests it as (a) scientific-notation conversion, (b) "which is largest?" comparisons, and (c) approximation inside DI.

- **Scientific notation:** N = a × 10^k with 1 ≤ a < 10. The **order of magnitude is k** (the power of 10). 4,80,00,000 = 4.8 × 10⁷ → order 7.
- **Indian vs international ⚠️:** 1 lakh = 10⁵, 1 crore = 10⁷ = 10 million; 1 billion = 10⁹ = 100 crore; 1 trillion = 10¹² = 1 lakh crore. Conversion errors here are a standard trap in economy-flavoured DI.
- **Comparing fractions ⚡**
  - Same numerator → **larger denominator = smaller fraction**.
  - Cross-multiplication for two fractions: a/b vs c/d → compare a·d with b·c.
  - **Add-to-both rule:** for a/b < 1, adding the same positive k to both terms moves the fraction **towards 1** (increases it); for a/b > 1 it decreases it.
  - Percentage conversion is often fastest: 7/13 ≈ 53.8%, 9/17 ≈ 52.9% → 7/13 is larger.
- **Approximation discipline:** round to **2 significant figures**, compute, then check whether the options are more than 5% apart. If they are, your estimate has already decided the answer.

---

## 7. Worked PYQ-pattern set

**Q1.** The least number which when divided by 12, 15 and 20 leaves remainder 5 in each case is:
**Sol.** LCM(12, 15, 20) = 60 → answer **65**.

**Q2.** Four bells ring at intervals of 6, 8, 12 and 18 seconds. If they ring together at 9:00:00 a.m., how many times will they ring together in the next 12 minutes?
**Sol.** LCM(6, 8, 12, 18) = 72 s. 12 min = 720 s → 720 ÷ 72 = **10 times** (excluding the 9:00:00 start; "in the next 12 minutes" excludes it — if the question says "including the start", answer 11). ⚠️ Read the wording.

**Q3.** The greatest number that divides 43, 91 and 183 leaving the same remainder in each case is:
**Sol.** Same *unknown* remainder → HCF of differences: 91−43 = 48, 183−91 = 92, 183−43 = 140 → HCF(48, 92, 140) = **4**.

**Q4.** The unit digit of 3^65 × 6^59 × 7^71 is:
**Sol.** 3^65: 65 ÷ 4 → r = 1 → 3. 6^59 → 6. 7^71: 71 ÷ 4 → r = 3 → 3. Product 3 × 6 × 3 = 54 → **4**.

**Q5.** HCF of two numbers is 12 and their LCM is 336. If one number is 84, the other is:
**Sol.** Product rule: (12 × 336)/84 = **48**.

**Q6.** If the HCF of 1/2, 3/4 and 5/6 is required:
**Sol.** HCF(1,3,5)/LCM(2,4,6) = **1/12**.

**Q7.** The largest four-digit number exactly divisible by 15, 25 and 40 is:
**Sol.** LCM = 600. 9999 ÷ 600 → remainder 399 → 9999 − 399 = **9600**.

**Q8.** √(0.0081) = ?
**Sol.** 0.0081 = 81 × 10⁻⁴ → root = 9 × 10⁻² = **0.09**. ⚠️ Decimal places in the root are **half** those in the number.

**Q9.** Which of 2^100, 3^75, 5^50, 6^25 is the greatest?
**Sol.** Bring to a common exponent of 25: 2^100 = 16^25, 3^75 = 27^25, 5^50 = 25^25, 6^25 = 6^25 → **3^75**.

**Q10.** A number when successively divided by 4 and 5 leaves remainders 1 and 4. What is the remainder when the same number is divided by 20?
**Sol.** Work back: last quotient 1 → 1 × 5 + 4 = 9 → 9 × 4 + 1 = 37. 37 ÷ 20 → remainder **17**.

---

## 8. Traps checklist ⚠️

1. **HCF × LCM = product** holds for **two** numbers only.
2. Bells/lights: decide whether the starting instant counts (**+1 or not**).
3. "Same remainder, value not given" → **HCF of differences**, not of the numbers.
4. Fractions: **HCF uses LCM of denominators** (and vice versa) — the crossover is deliberately confusing.
5. **1 is neither prime nor composite; 2 is the only even prime; 0 is even and is a whole number.**
6. Divisibility by a composite → split into **co-prime** factors only.
7. Unit-digit cycles: remainder **0** means the **4th** term, not the 1st.
8. Square root of a decimal: halve the decimal places.
9. **Crore ↔ million** conversions in "order of magnitude" questions.
10. In "greatest 4-digit number divisible by…", **subtract** the remainder; in "least 4-digit number", **add** (divisor − remainder).

---

## 9. Rapid-fire recall

- Factors of N = a^p·b^q → **(p+1)(q+1)**.
- **Perfect square never ends in 2, 3, 7, 8**; has an **odd** number of factors.
- Unit-digit cycle length is **4** for 2, 3, 7, 8; **2** for 4, 9; **1** for 0, 1, 5, 6.
- √ of numbers ending in 5: (n5)² = n(n+1)|25.
- Co-prime ⇒ **LCM = product, HCF = 1**.
- Order of magnitude = the **exponent of 10** in scientific notation.
- 1 crore = 10⁷ = 10 million; 1 trillion = 1 lakh crore.

[Index](README.md) · [Next: Ratio, Percentage, Profit & Interest →](02-Ratio-Proportion-Percentage-Profit-and-Interest.md)
