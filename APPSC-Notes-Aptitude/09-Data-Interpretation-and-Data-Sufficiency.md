# 09 · Data Interpretation and Data Sufficiency

[← Venn & Syllogism](08-Venn-Diagrams-Syllogisms-and-Logical-Reasoning.md) · [Index](README.md) · [Next: Psychological Abilities →](10-Psychological-Abilities-Decision-Making-and-EI.md)

**Syllabus phrase covered:** *"data interpretation and data sufficiency"*

> **Placement note:** in some printings of the notification, "Data Analysis / Data Interpretation" is listed as its own head rather than inside Section A. Either way it is examined in Paper-II and shares its entire toolkit (percentage, ratio, average) with Section A, so it belongs in this series. Check your year's notification for the formal heading.

**PYQ signal:** typically **one or two sets of 4–5 questions each**, built on a table, a bar chart or a pie chart, plus a few standalone data-sufficiency questions. DI is where a prepared candidate gains 5–8 marks and an unprepared one loses fifteen minutes. **The skill being tested is not arithmetic — it is reading and estimating.**

---

# PART I — DATA INTERPRETATION

## 1. The chart families

| Type | What it shows | The habit it demands |
|---|---|---|
| **Table** | Exact values, many variables | Read row/column headers and the **unit line** before anything else |
| **Bar chart** (simple, grouped, stacked) | Comparison across categories | Read the **axis scale**; in stacked bars, values are **cumulative** ⚠️ |
| **Line graph** | Trend over time | Distinguish **level** from **rate of change** |
| **Pie chart** | Share of a whole | Convert **degrees ↔ percentage**: 3.6° = 1% ⚡ |
| **Mixed / combination** | Two charts feeding each other | Identify which chart supplies the base value |
| **Caselet** | A paragraph of data with no chart | **Tabulate it yourself** before answering anything |
| **Radar / web** | Multi-parameter comparison | Rare; read like a bar chart on a circle |

## 2. The reading protocol ⭐ (do this before question 1 of the set)

1. **Title** — what the data is about.
2. **Units** — ₹ crore? lakh tonnes? percentage? "in thousands"? ⚠️ *The single most costly DI error is a units error.*
3. **Axis scale** and whether it starts at zero.
4. **Footnotes** — "figures are provisional", "excluding exports" — these exist to be used.
5. **Totals** — if a total row or column exists, note it; many questions are one step from it.

Spend **30–40 seconds** on this. It pays for itself in the first question.

## 3. The formulae DI actually uses ⭐

| Ask | Formula |
|---|---|
| Percentage share | (part / total) × 100 |
| **Percentage change** | **(new − old)/old × 100** ⚠️ always divide by the **old/base** value |
| Percentage point change | simple subtraction of two percentages — **not** a percentage change ⚠️ |
| Ratio of two quantities | divide directly; simplify before computing |
| **CAGR (approx.)** | (final/initial)^(1/n) − 1; for exam purposes, estimate with the **Rule of 72** or simple averaging |
| Average over n periods | total ÷ n |
| Pie: value of a sector | (sector angle / 360) × total, or (sector % ) × total |
| Combining two charts | (share from chart 1) × (total from chart 2) |

## 4. Estimation craft ⚡⚡ (this is the real skill)

- **Look at the options first.** If they are far apart (say 12%, 24%, 38%, 51%), a rough estimate settles it; only compute exactly when two options are within ~5%.
- **Round to 2 significant figures**: 4,873 → 4,900 → 4,900/12,100 ≈ 0.40.
- **Use the fraction table from [File 02](02-Ratio-Proportion-Percentage-Profit-and-Interest.md):** recognising that 3/8 = 37.5% or 1/6 = 16.7% removes long division entirely.
- **Percentage change by fraction ⚡:** from 240 to 300 is +60 on 240 = 60/240 = **1/4 = 25%**. Convert to a familiar fraction rather than dividing.
- **Comparison without computation:** to rank several ratios a/b, compare them against a common benchmark (½, ⅓) instead of evaluating each.
- **Don't compute what isn't asked.** "By what percentage is A more than B" needs one division, not two full values.

## 5. Question types and their shortcuts

| Type | Shortcut |
|---|---|
| "Which year saw the **highest percentage increase**?" | Compare **increase ÷ previous value** by eye — the biggest jump on a small base usually wins; don't compute all of them |
| "What is the **average** of…?" | Use the deviation method from [File 03](03-Averages-Central-Tendencies-and-Alligation.md) |
| "**Approximately what percentage**…" | Round hard; the word *approximately* is permission to estimate |
| "The **ratio** of X to Y is…" | Cancel common factors and units first |
| "If the trend continues, in 2026…" | Extrapolate with the **average growth** of the given years |
| "What is the **difference**…?" | Subtract *before* multiplying by a common factor — one operation instead of two |
| Pie + table combination | Compute the **absolute value** of the pie sector once, then reuse it for every question in the set |

⚠️ **Set-level strategy:** in a 5-question set, questions 1–3 are usually direct and question 4–5 involve combining charts. **Attempt the set only if the first question falls in under a minute**; if the data is dense and the units awkward, skip the whole set — the cost of a bad set is five minutes for one or two marks.

---

# PART II — DATA SUFFICIENCY ⭐

## 6. The format

You are given a question and **two statements (I and II)**, and asked whether the statements are enough to answer — **not what the answer is**. The standard option grid:

| Option | Meaning |
|---|---|
| (a) | Statement **I alone** is sufficient, but II alone is not |
| (b) | Statement **II alone** is sufficient, but I alone is not |
| (c) | **Both together** are sufficient, but neither alone is |
| (d) | **Each alone** is sufficient |
| (e) | **Both together are still not sufficient** (more data needed) |

⚠️ APPSC sometimes uses a three-statement variant ("which of the statements can be dispensed with?"). The logic is identical; read the option wording carefully — it changes between papers.

## 7. The method ⭐⭐

1. **Read the question first and note exactly what is being asked** (a value? a ratio? a yes/no?).
2. Evaluate **Statement I alone**, covering statement II with your hand — literally, so you cannot contaminate it.
3. Evaluate **Statement II alone**, forgetting I completely. *This is where candidates lose marks: carrying information from I into II.*
4. Only if both fail individually, combine them.
5. **Stop as soon as sufficiency is established. Do not solve for the value.** ⚡ Finding the answer is wasted time; you only need to know that a unique answer exists.

## 8. Sufficiency rules of thumb ⚡

- **n independent linear equations determine n unknowns.** Two statements giving the same relation twice are *not* two equations.
- A statement that gives a **ratio** cannot fix an absolute value on its own; it needs one absolute anchor.
- For a **yes/no** question, a statement is sufficient if it forces a **consistent** yes or a consistent no — a definite "no" is just as sufficient as a definite "yes". ⚠️ Candidates wrongly mark "insufficient" when the answer is no.
- Beware **quadratics**: an equation giving x² = 16 yields x = ±4 → **not sufficient** unless the context (age, count, length) rules out the negative root.
- In arrangement/sequence data sufficiency, sufficiency means **exactly one** arrangement survives.
- If Statement I is a **special case** of Statement II (or vice versa), option (d) is unlikely — check for redundancy.

---

## 9. Worked PYQ-pattern set

### Set A — Table

Production of rice (in lakh tonnes) in four districts:

| District | 2021 | 2022 | 2023 |
|---|---|---|---|
| P | 40 | 48 | 60 |
| Q | 55 | 55 | 66 |
| R | 30 | 39 | 42 |
| S | 75 | 60 | 69 |
| **Total** | **200** | **202** | **237** |

**Q1.** Which district recorded the highest percentage increase in production from 2021 to 2023?
**Sol.** P: 20/40 = **50%**; Q: 11/55 = 20%; R: 12/30 = 40%; S: −6/75 = −8% → **P**. ⚡ *Method point:* compare **rise ÷ base**, never rise alone — R's rise looks respectable but sits on a small base, and S actually fell.

**Q2.** The production of S in 2022 was what percentage of the total production in 2022?
**Sol.** 60/202 ≈ **29.7% ≈ 30%**.

**Q3.** What is the average production of district Q over the three years?
**Sol.** (55 + 55 + 66)/3 = 176/3 = **58.67 lakh tonnes**.

**Q4.** By what percentage did the total production rise from 2022 to 2023?
**Sol.** 35/202 ≈ **17.3%**.

**Q5.** The ratio of P's production in 2023 to S's in 2021 is:
**Sol.** 60 : 75 = **4 : 5**.

### Set B — Pie chart

A family's monthly expenditure of ₹36,000 is divided as: Food 120°, Rent 90°, Education 60°, Transport 45°, Others 45°.

**Q6.** The amount spent on Rent is:
**Sol.** 90/360 = 25% → **₹9,000**.

**Q7.** Food expenditure exceeds Education expenditure by:
**Sol.** (120 − 60)/360 × 36,000 = 1/6 × 36,000 = **₹6,000**.

**Q8.** Transport expenditure as a percentage of Food expenditure is:
**Sol.** 45/120 = 37.5% → **37.5%**. ⚡ (Angles can be compared directly; no need to convert to rupees.)

### Set C — Data sufficiency

**Q9.** *What is the two-digit number?*
 I. The sum of its digits is 9. II. The difference between the digits is 3.
**Sol.** I alone: 18, 27, 36, 45, 54, 63, 72, 81, 90 — insufficient. II alone: many — insufficient. Together: digits summing to 9 and differing by 3 → 3 and 6 → 36 or 63 → **still two answers → option (e), both together are not sufficient.** ⚠️ A classic: "together" does not automatically mean sufficient.

**Q10.** *How many students are in the class?*
 I. If 4 more students join, the strength becomes divisible by 5. II. The strength is between 28 and 34.
**Sol.** I alone: n ≡ 1 (mod 5) — infinitely many, insufficient. II alone: 29–33, insufficient. Together: the only value in that range with n ≡ 1 (mod 5) is **31** → unique → **(c)**. ⚠️ Whenever a statement says "between a and b", check whether the endpoints would change the count — examiners exploit that ambiguity.

**Q11.** *Is x greater than y?*
 I. x² > y². II. x − y > 0.
**Sol.** I alone: x = −5, y = 3 gives x² > y² but x < y → insufficient. II alone: x − y > 0 ⇒ x > y always → **sufficient → option (b)**.

**Q12.** *What is A's monthly salary?*
 I. A's salary is 40% of B's. II. B's salary is ₹50,000.
**Sol.** Neither alone (I is a ratio, II is about B) → together A = ₹20,000 → **(c)**.

---

## 10. Traps checklist ⚠️

1. **Units** — "in thousands", "in ₹ crore", "in %". Read them twice.
2. **Percentage change divides by the OLD value**, not the new one.
3. **Percentage vs percentage point** — a rise from 20% to 25% is 5 percentage points but a **25% increase**.
4. Stacked bars are **cumulative**; read segment values by subtraction.
5. Pie charts: **1% = 3.6°**; comparisons between sectors can be done in degrees directly.
6. "Highest increase" ≠ "highest percentage increase" — check which is asked.
7. Data sufficiency: **evaluate each statement in isolation**, then combine. Never carry over.
8. In DS, **do not solve** — stop at sufficiency.
9. In DS, a definite **"no"** is a sufficient answer to a yes/no question.
10. x² = k gives **two roots** — usually insufficient.
11. If the first question of a DI set takes more than a minute, **abandon the set**.
12. Averages in DI: check whether the question wants the average of the **values** or of the **percentages** (these differ when the bases differ).

---

## 11. Rapid-fire recall

- Pie: **1% = 3.6°**; sector value = (angle/360) × total.
- % change = **(new − old)/old × 100**.
- Percentage point ≠ percentage change.
- Combining charts: **share × total**.
- Estimate first, compute only when options are close.
- DS grid: (a) I only · (b) II only · (c) both together · (d) either alone · (e) insufficient even together.
- DS: n unknowns need **n independent** equations; ratios need an absolute anchor; quadratics usually fail.
- **Stop at sufficiency — never solve.**

[← Venn & Syllogism](08-Venn-Diagrams-Syllogisms-and-Logical-Reasoning.md) · [Index](README.md) · [Next: Psychological Abilities →](10-Psychological-Abilities-Decision-Making-and-EI.md)
