# 08 · Venn Diagrams · Syllogisms · Statement-Based Logical Reasoning

[← Clocks & Calendars](07-Clocks-Calendars-and-Ages.md) · [Index](README.md) · [Next: Data Interpretation & Sufficiency →](09-Data-Interpretation-and-Data-Sufficiency.md)

**Syllabus phrases covered:** *"Venn diagrams"*, *"logical reasoning and analytical ability"*

**PYQ signal:** Venn diagrams are **named in the syllabus** and appear in both forms — the **logical** form ("which diagram best represents Doctors, Men, Human beings?") and the **numerical** form (set formulae). Syllogism and statement–conclusion questions carry the "logical reasoning" phrase. Together, 5–8 questions. This block rewards **discipline over speed**: almost every mark lost here is lost to importing real-world knowledge into a formal question.

---

# PART I — LOGICAL VENN DIAGRAMS

## 1. The four relationships

Every pair of classes stands in exactly one of these relations:

| Relation | Diagram | Example |
|---|---|---|
| **Wholly included** (subset) | small circle inside big | Cows ⊂ Animals |
| **Partially overlapping** | two intersecting circles | Doctors ∩ Women |
| **Wholly disjoint** | two separate circles | Cats · Dogs |
| **Identical / co-extensive** | one circle | Rare in exams |

## 2. The method ⭐

1. Take the classes **pairwise** and decide the relation for each pair — three pairs for three classes.
2. Choose the option diagram that satisfies **all** pairs simultaneously.
3. Test each option by asking: *"does this diagram assert anything the words don't?"*

**Standard triples to recognise instantly ⚡**

| Classes | Structure |
|---|---|
| Cow, Animal, Dog | Cow and Dog are **separate circles inside** Animal |
| Doctor, Man, Human being | Doctor ∩ Man, both **inside** Human being |
| Table, Chair, Furniture | Two disjoint circles inside a big one |
| Pen, Pencil, Stationery | Same as above |
| Andhra Pradesh, India, Asia | Three **concentric** circles |
| Engineer, Father, Male | Overlapping pairs, all inside Male? — ⚠️ **no**: Father ⊂ Male, Engineer ∩ Male (engineers may be women) → Engineer partially overlaps Male, Father wholly inside Male |
| Teacher, Graduate, Woman | All three mutually overlapping |
| Sun, Moon, Star | Sun ⊂ Star; Moon disjoint from both |

⚠️ **The recurring trap:** distinguishing "all professionals could be male" (world knowledge) from what the words *require*. Use only the definitional relation.

---

# PART II — NUMERICAL VENN (SET THEORY) ⭐⭐

## 3. Two-set formula

**n(A ∪ B) = n(A) + n(B) − n(A ∩ B)**

- Only A = n(A) − n(A ∩ B); only B = n(B) − n(A ∩ B).
- Neither = **Total − n(A ∪ B)**.

## 4. Three-set formula ⭐

**n(A ∪ B ∪ C) = n(A) + n(B) + n(C) − n(A∩B) − n(B∩C) − n(C∩A) + n(A∩B∩C)**

**Region-by-region reading (fill the diagram from the centre outwards ⚡):**

| Region | Value |
|---|---|
| All three | n(A∩B∩C) = *c* |
| Exactly A and B | n(A∩B) − c |
| Exactly A only | n(A) − n(A∩B) − n(A∩C) + c |
| **Exactly two** | n(A∩B) + n(B∩C) + n(C∩A) − **3c** |
| **At least two** | n(A∩B) + n(B∩C) + n(C∩A) − **2c** |
| Exactly one | n(A∪B∪C) − (exactly two) − c |

⚠️ "**Exactly two**" subtracts **3c**; "**at least two**" subtracts **2c**. Mixing these up is the classic error, and both wrong answers are always among the options.

⚡ **Always fill the centre first, then the pair-regions, then the singles.** Working outside-in guarantees double-counting.

## 5. Maximum–minimum questions
- **Maximum overlap** of A and B = the **smaller** of n(A), n(B).
- **Minimum overlap** = n(A) + n(B) − Total (if positive; otherwise 0).
 *Example:* in a class of 100, 70 play cricket and 60 play football → minimum playing both = 70 + 60 − 100 = **30**; maximum = 60.

---

# PART III — SYLLOGISM ⭐⭐

## 6. The four standard propositions

| Type | Form | Name |
|---|---|---|
| **A** | **All** S are P | universal affirmative |
| **E** | **No** S is P | universal negative |
| **I** | **Some** S are P | particular affirmative |
| **O** | **Some** S are not P | particular negative |

**Immediate inferences (conversions) — memorise ⚡**

| Statement | Valid immediate inference |
|---|---|
| **All A are B** | **Some B are A** (and Some A are B) — ⚠️ *not* "All B are A" |
| **No A is B** | **No B is A**, and **Some A are not B** |
| **Some A are B** | **Some B are A** |
| **Some A are not B** | **nothing converts** ⚠️ (you may *not* infer "Some B are not A") |

## 7. The circle method (the only reliable technique)

1. Draw the **minimum** diagram the statements force — nothing more.
2. Test each conclusion: it **follows only if it is true in EVERY possible diagram** consistent with the statements.
3. If you can draw even **one** valid diagram in which the conclusion fails, the conclusion **does not follow**.

**Rules of thumb ⚡**
- Two **particular** statements (I/O) give **no definite conclusion**.
- Two **negative** statements give **no definite conclusion**.
- If one premise is particular, the conclusion **must** be particular; if one is negative, the conclusion must be negative.
- The **middle term** (the common term) must be distributed at least once.

## 8. The "possibility" rule ⭐ (the modern APPSC/banking style)

Conclusions phrased as "**Some A are B is a possibility**" or "**All A being B is a possibility**" follow whenever the statements **do not forbid** it.

- **All A are B** → "Some A are not B" ✘, but "All B being A is a possibility" ✔.
- **No A is B** → any possibility involving A ∩ B is ✘.
- ⚡ Rule: a **possibility conclusion is TRUE unless a negative statement (E or O) blocks it.**

## 9. Either–or (complementary pairs) ⭐

When **neither conclusion individually follows**, but **together they exhaust all cases** and the two overlap on the same subject and predicate, mark "**either I or II follows**".

The complementary pairs are:
- **Some A are B** / **Some A are not B**
- **All A are B** / **Some A are not B**
- **No A is B** / **Some A are B**

⚠️ Test both conditions: (i) individually neither follows, (ii) they form one of the pairs above. Only then is "either–or" correct.

---

# PART IV — STATEMENT-BASED REASONING

## 10. Statement and conclusion / assumption / argument / course of action

| Question type | The test |
|---|---|
| **Statement → Conclusion** | Does the conclusion follow **from the statement alone**, without any outside knowledge? |
| **Statement → Assumption** | An assumption is something **taken for granted** and **necessary** for the statement to make sense. Apply the **negation test ⚡**: negate the assumption; if the statement collapses, it *is* an assumption |
| **Statement → Argument** | A **strong** argument is (i) directly related, (ii) practically significant, (iii) not a mere example, personal opinion, or ambiguous generality |
| **Statement → Course of action** | A course of action is proper if it (i) addresses the problem, (ii) is **practicable/implementable**, and (iii) is **within the authority's power** |
| **Cause and effect** | The cause must **precede** the effect and be **independent**; watch for a common third cause |
| **Statement → Inference** | An inference is *derived*, not stated; grade as definitely/probably true, data inadequate, probably/definitely false |

### 10.1 The governing discipline ⭐⭐
**Answer from the passage only.** In this whole block the examiner is testing whether you can suppress what you know. If a statement says "the government has announced free bus travel for women", an option that reads "the scheme will improve women's workforce participation" **does not follow** — it may well be true in the world, but it is not in the statement.

### 10.2 Word-strength filter ⚡
Options containing **"all", "only", "never", "must", "every", "the best", "cannot"** are usually **too strong** to follow from a modest statement. Options containing **"some", "may", "many", "likely"** are usually safe. This one filter resolves a large share of statement–conclusion questions in seconds.

### 10.3 Course-of-action extras
- Two courses of action can both be right when one is **short-term** (immediate relief) and the other **long-term** (structural fix) — "both follow" is a real answer.
- Reject actions that are **punitive without process**, **impossible in scale**, or **outside the stated body's jurisdiction**.

---

## 11. Worked PYQ-pattern set

**Q1.** Which diagram best represents the relationship among **Doctors, Women, Human beings**?
**Sol.** Doctors and Women **overlap** (some doctors are women), and both lie **wholly within** Human beings.

**Q2.** In a survey of 100 people, 60 read newspaper A, 45 read B and 25 read both. How many read neither?
**Sol.** A ∪ B = 60 + 45 − 25 = 80 → neither = **20**.

**Q3.** In a class of 60, 30 play cricket, 25 play hockey, 20 play football; 12 play cricket and hockey, 10 hockey and football, 8 cricket and football, and 5 play all three. How many play at least one game?
**Sol.** 30 + 25 + 20 − 12 − 10 − 8 + 5 = **50**.

**Q4.** In Q3, how many play **exactly two** games?
**Sol.** (12 + 10 + 8) − 3(5) = 30 − 15 = **15**.

**Q5.** In Q3, how many play **exactly one** game?
**Sol.** 50 − 15 − 5 = **30**.

**Q6.** *Statements:* All pens are books. All books are papers. *Conclusions:* (I) All pens are papers. (II) Some papers are pens.
**Sol.** Chain of universals → **both follow**.

**Q7.** *Statements:* Some flowers are red. All red things are beautiful. *Conclusions:* (I) Some flowers are beautiful. (II) All flowers are beautiful.
**Sol.** I follows (the red flowers are beautiful). II does not — the non-red flowers are unconstrained. **Only I follows.**

**Q8.** *Statements:* No student is lazy. Some lazy people are rich. *Conclusions:* (I) Some rich people are not students. (II) No rich person is a student.
**Sol.** The lazy-and-rich people are not students → **only I follows**. II overreaches (other rich people may be students).

**Q9.** *Statements:* All cats are dogs. *Conclusion:* All dogs being cats is a possibility.
**Sol.** No negative statement blocks it → **it follows** (possibility rule).

**Q10.** *Statement:* "Use our shampoo for silky hair." *Assumption:* (I) People want silky hair. (II) Only this shampoo gives silky hair.
**Sol.** Negation test: if people did **not** want silky hair, the advertisement is pointless → I is assumed. II uses "only" — too strong, and not necessary. **Only I is implicit.**

**Q11.** *Statement:* Heavy rains have flooded several low-lying colonies of the city. *Courses of action:* (I) People in those colonies should be shifted to safer places immediately. (II) The civic body should be asked to review the storm-water drainage plan.
**Sol.** I is the short-term relief, II the long-term fix; both are practicable and within the authority's power → **both follow**.

**Q12.** In a group of 200 people, 120 like tea and 100 like coffee. What is the **minimum** number who like both?
**Sol.** 120 + 100 − 200 = **20**.

---

## 12. Traps checklist ⚠️

1. **"All A are B" never gives "All B are A."** Only "Some B are A".
2. **"Some A are not B" converts to nothing.**
3. Two particular premises, or two negative premises, yield **no conclusion**.
4. A conclusion follows only if true in **every** possible diagram — hunt for the counter-diagram.
5. "Either–or" needs **both** conditions: neither follows alone **and** they form a complementary pair.
6. **Possibility conclusions are true unless a negative premise blocks them.**
7. Set theory: **exactly two = Σ pairs − 3c**; **at least two = Σ pairs − 2c**.
8. Three-set formula: the triple intersection is **added back**, not subtracted.
9. Statement–conclusion: **no outside knowledge**, however obviously true.
10. Options with **all / only / never / must** are usually wrong; options with **some / may** are usually safe.
11. Assumption ≠ inference. An assumption comes **before** the statement (it is presupposed); an inference comes **after** it.
12. Logical Venn: use the **definitional** relation, not empirical likelihood.

---

## 13. Rapid-fire recall

- **n(A∪B) = n(A) + n(B) − n(A∩B)**; three-set: **+ triple back**.
- Exactly two = **Σpairs − 3c**; at least two = **Σpairs − 2c**.
- Min overlap = **n(A) + n(B) − Total**; max overlap = **min(n(A), n(B))**.
- A / E / I / O = All are / No is / Some are / Some are not.
- Conversions: **A → I**, **E → E**, **I → I**, **O → nothing**.
- Possibility follows unless a **negative** premise blocks it.
- Complementary pairs: (Some A are B, Some A are not B); (All A are B, Some A are not B); (No A is B, Some A are B).
- **Negation test** identifies assumptions.
- **Answer from the statement alone.**

[← Clocks & Calendars](07-Clocks-Calendars-and-Ages.md) · [Index](README.md) · [Next: Data Interpretation & Sufficiency →](09-Data-Interpretation-and-Data-Sufficiency.md)
