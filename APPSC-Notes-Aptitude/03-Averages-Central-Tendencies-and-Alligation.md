# 03 · Averages, Central Tendencies (Mean · Median · Mode) and Alligation

[← Ratio & Percentage](02-Ratio-Proportion-Percentage-Profit-and-Interest.md) · [Index](README.md) · [Next: Time, Work, Speed & Distance →](04-Time-Work-Speed-and-Distance.md)

**Syllabus phrase covered:** *"central tendencies — mean, median, mode including weighted mean"*

**PYQ signal:** APPSC names this topic **explicitly in the syllabus**, which is why it appears nearly every year — usually as (i) a definitional question on median/mode of a small data set, (ii) a weighted-mean or combined-mean calculation, or (iii) the classic "average changes when a person is replaced" problem. Alligation is not named in the syllabus but is the fastest tool for mixture and average questions, and mixture questions do appear.

---

## 1. Average (arithmetic mean)

**Average = Sum of observations ÷ Number of observations** → **Sum = Average × n**

> ⚡ **The one habit that fixes this whole chapter:** stop thinking in averages, think in **sums**. Almost every average question is "what happened to the total?"

### 1.1 Standard results

| Set | Average |
|---|---|
| First n natural numbers | **(n + 1)/2** |
| Squares of first n naturals | (n + 1)(2n + 1)/6 |
| Cubes of first n naturals | n(n + 1)²/4 |
| First n even numbers | **n + 1** |
| First n odd numbers | **n** |
| Any set of consecutive numbers / an AP | **(first + last)/2** ⚡ (also = the middle term) |

### 1.2 The deviation (assumed-mean) shortcut ⚡
Pick a convenient base A, average the deviations, add back:
Average of 342, 348, 351, 357, 362 → base 350 → deviations −8, −2, +1, +7, +12 → sum 10 → 10/5 = 2 → **352**.

### 1.3 Change-in-average results ⭐

| Event | Result |
|---|---|
| A new member joins and the average rises by d | new member's value = **old average + (n + 1)d** |
| A member leaves and the average rises by d | leaver's value = old average − (n − 1)d |
| One member is **replaced** and the average changes by d | **difference between the two people = n × d** ⚡ |
| k members' values each increased by x | average rises by **kx/n** |

*Replacement is the most-asked form:* "The average weight of 8 men increases by 2.5 kg when a new man replaces one weighing 65 kg." → difference = 8 × 2.5 = 20 → new man = **85 kg**.

### 1.4 Combined (weighted) average ⭐
For groups of sizes n₁, n₂ with averages A₁, A₂:

**Combined average = (n₁A₁ + n₂A₂)/(n₁ + n₂)**

**Weighted mean** in general = **Σ(wᵢxᵢ)/Σwᵢ**. This is the syllabus's named "weighted mean" — expect a marks-with-credits or price-with-quantity question.

⚠️ **The classic error:** the average of two averages is **not** the combined average unless the groups are equal in size.

### 1.5 Averages that are *not* arithmetic means ⭐

| Mean | Formula | Use it when |
|---|---|---|
| **Arithmetic (AM)** | (a + b)/2 | quantities add |
| **Geometric (GM)** | √(ab) | **growth rates, ratios, percentage change over periods** |
| **Harmonic (HM)** | **2ab/(a + b)** | **rates over the same distance/quantity** — average speed! |

- **AM ≥ GM ≥ HM** always (equal only when all values are equal); **GM² = AM × HM** for two numbers.
- ⚡ **Average speed for equal distances at speeds x and y = 2xy/(x + y)** — this is the harmonic mean and is the single most-tested "average" formula in the paper. (For equal *times*, the answer is the plain arithmetic mean.)

---

## 2. Median

**Median = the middle value when data is arranged in order.**

- **n odd:** median = the **((n+1)/2)th** value.
- **n even:** median = **average of the (n/2)th and (n/2 + 1)th** values.
- ⚠️ **You must sort the data first.** APPSC's favourite median trap is a jumbled list.
- Median is **resistant to extreme values** — it is the right central tendency for income/wealth-type skewed data (a fact sometimes asked conceptually).

**Grouped data:** Median = L + [(n/2 − cf)/f] × h, where L = lower limit of the median class, cf = cumulative frequency before it, f = its frequency, h = class width.

---

## 3. Mode

**Mode = the most frequently occurring value.**

- A data set may be **unimodal, bimodal, multimodal, or have no mode** (all values distinct) — the "no mode" option is a real APPSC answer choice.
- **Grouped data:** Mode = L + [(f₁ − f₀)/(2f₁ − f₀ − f₂)] × h.
- Mode is the only central tendency usable for **qualitative/nominal data** (most common blood group, most preferred crop) — a favourite conceptual question.

### 3.1 The empirical relation ⭐
For a moderately skewed distribution:

**Mode = 3 × Median − 2 × Mean**

⚡ Given any two of the three, produce the third in one line. Learn it in this exact form — the rearrangement (Mean − Mode = 3(Mean − Median)) is the same statement.

### 3.2 Which is where in a skewed curve

| Distribution | Order |
|---|---|
| **Symmetric (normal)** | **Mean = Median = Mode** |
| **Positively skewed** (long right tail) | **Mode < Median < Mean** |
| **Negatively skewed** (long left tail) | Mean < Median < Mode |

---

## 4. Comparison table (learn as a block) ⭐

| | Mean | Median | Mode |
|---|---|---|---|
| Definition | sum ÷ count | middle value | most frequent |
| Uses every observation? | **Yes** | No | No |
| Affected by extreme values? | **Yes, badly** | No | No |
| Can be computed for qualitative data? | No | Ordinal only | **Yes** |
| Always unique? | Yes | Yes | **No** |
| Suited to | symmetric numeric data | skewed data (income) | categorical data |
| Algebraic treatment | Possible | Not really | Not really |

**Other positional measures:** quartiles Q₁, Q₂ (= median), Q₃; deciles (9); percentiles (99). **Q₂ = median = D₅ = P₅₀.**

**Dispersion one-liners** (occasionally asked): Range = max − min; Quartile deviation = (Q₃ − Q₁)/2; Mean deviation = Σ|x − x̄|/n; **Standard deviation σ = √[Σ(x − x̄)²/n]**; **Variance = σ²**; **Coefficient of variation = (σ/x̄) × 100** — the measure used to compare consistency between two data sets (**lower CV = more consistent** ⚡).

---

## 5. Mixtures and alligation ⚡⚡

**Alligation is a shortcut for weighted averages.** When two ingredients at prices/concentrations **c (cheaper)** and **d (dearer)** are mixed to give mean **m**:

```
        c                 d
              \       /
                 m
              /       \
          (d − m)   (m − c)

   Quantity of cheaper : Quantity of dearer = (d − m) : (m − c)
```

⚡ **Read it as:** the ratio of quantities is the **inverse** of the distances from the mean. If the mean is closer to the dearer price, more of the dearer ingredient was used.

**Use alligation for:** price mixtures, milk-and-water, alloy composition, average marks of two sections, average speed over two legs, profit percentages of two lots, interest rates of two investments — *any* question of the form "two groups combine to a known average, find the ratio".

### 5.1 The replacement formula ⭐
A vessel holds x litres of pure liquid; y litres are removed and replaced with water; repeated n times. Then

**Liquid remaining = x · (1 − y/x)ⁿ = x[(x − y)/x]ⁿ**

and the ratio liquid : water = [(x−y)/x]ⁿ : 1 − [(x−y)/x]ⁿ.

*Example:* 40 L of milk, 4 L removed and replaced by water, thrice → 40 × (36/40)³ = 40 × 0.729 = **29.16 L** milk.

### 5.2 Adding pure ingredient to change concentration
If a mixture of M litres is a% milk and you add W litres of water, new % = (aM/100)/(M + W) × 100. Set equal to the target and solve for W — or, faster, apply alligation with pure water treated as 0% milk.

---

## 6. Worked PYQ-pattern set

**Q1.** The average of the first 50 natural numbers is:
**Sol.** (n + 1)/2 = **25.5**.

**Q2.** The average age of 30 students is 12 years. If the teacher's age is included, the average rises by 1 year. The teacher's age is:
**Sol.** Old average + (n + 1)d = 12 + 31 × 1 = **43 years**.

**Q3.** The average weight of 20 boys is 48 kg. A boy weighing 55 kg leaves and another joins; the average becomes 48.5 kg. The new boy's weight is:
**Sol.** Replacement: difference = 20 × 0.5 = 10 → 55 + 10 = **65 kg**.

**Q4.** A car covers the first half of a journey at 40 km/h and the second half at 60 km/h. Its average speed is:
**Sol.** Equal distances → harmonic mean = 2(40)(60)/100 = **48 km/h**. ⚠️ Not 50.

**Q5.** Find the median of 12, 7, 19, 3, 15, 9.
**Sol.** Sort: 3, 7, 9, 12, 15, 19 → n even → (9 + 12)/2 = **10.5**.

**Q6.** For a distribution, mean = 45 and median = 42. The mode is:
**Sol.** Mode = 3(42) − 2(45) = 126 − 90 = **36**.

**Q7.** In a class of 60, the average marks of 40 boys is 65 and of 20 girls is 80. The class average is:
**Sol.** (40×65 + 20×80)/60 = (2600 + 1600)/60 = **70**.

**Q8.** In what ratio must rice at ₹42/kg be mixed with rice at ₹54/kg so that the mixture is worth ₹48/kg?
**Sol.** Alligation: (54 − 48) : (48 − 42) = 6 : 6 = **1 : 1**.

**Q9.** In what ratio must water be mixed with milk costing ₹60 per litre so that by selling the mixture at ₹60 per litre the seller gains 20%?
**Sol.** SP = 60 with 20% gain → CP of mixture = 50. Alligation between water (0) and milk (60) at mean 50 → water : milk = (60 − 50) : (50 − 0) = **1 : 5**.

**Q10.** From a 60-litre vessel of pure milk, 10 litres are drawn and replaced with water. This is repeated once more. Milk remaining is:
**Sol.** 60 × (50/60)² = 60 × 25/36 = **41⅔ litres**.

**Q11.** The mean of 5 observations is 20. If one observation, 18, is wrongly recorded and should be 28, the corrected mean is:
**Sol.** Sum rises by 10 → mean rises by 10/5 = 2 → **22**.

**Q12.** Two batsmen have the same average of 40 runs, with standard deviations 12 and 8. Who is more consistent?
**Sol.** CV = σ/x̄ → the one with **σ = 8** (lower CV) is more consistent.

---

## 7. Traps checklist ⚠️

1. **Sort before finding the median.** Always.
2. Average of two averages ≠ combined average unless the group sizes are equal — use **weighted** mean.
3. **Equal distances → harmonic mean (2xy/(x+y)); equal times → arithmetic mean.**
4. Replacement problems: the difference between the two people is **n × change**, not the change itself.
5. **Mode = 3 Median − 2 Mean** (not the other way round). Check with a symmetric set where all three are equal.
6. "No mode" is a legitimate answer for all-distinct data.
7. In alligation, the ratio is of the **quantities**, and it is the *cross* of the differences.
8. Replacement formula uses the **fraction removed of the whole vessel**, so keep x as the *total* volume.
9. When a wrong observation is corrected, adjust the **sum** first.
10. Positively skewed order: **Mode < Median < Mean** (alphabetical-ish: mode is leftmost with the tail on the right).

---

## 8. Rapid-fire recall

- Average of consecutive numbers = **(first + last)/2**.
- New member: value = old average + (n + 1) × rise. Replacement: difference = n × change.
- **Combined average = (n₁A₁ + n₂A₂)/(n₁ + n₂).**
- **AM ≥ GM ≥ HM**; GM² = AM × HM.
- Average speed (equal distances) = **2xy/(x + y)**.
- **Mode = 3 Median − 2 Mean.**
- Alligation ratio = **(d − m) : (m − c)**.
- Replacement: remaining = **x[(x − y)/x]ⁿ**.
- Lower **coefficient of variation** = greater consistency.

[← Ratio & Percentage](02-Ratio-Proportion-Percentage-Profit-and-Interest.md) · [Index](README.md) · [Next: Time, Work, Speed & Distance →](04-Time-Work-Speed-and-Distance.md)
