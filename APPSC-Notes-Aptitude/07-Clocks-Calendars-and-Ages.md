# 07 · Clocks · Calendars · Problems on Ages

[← Series & Coding](06-Series-Coding-Decoding-Relations-and-Arrangements.md) · [Index](README.md) · [Next: Venn, Syllogism & Logical Reasoning →](08-Venn-Diagrams-Syllogisms-and-Logical-Reasoning.md)

**Syllabus phrase covered:** *"problems based on clocks, calendar and age"*

**PYQ signal:** a small but **absolutely predictable** block, 3–5 questions, named verbatim in the syllabus. Every question comes from one of about eight templates. Learn the eight and this chapter is a guaranteed 3–5 marks in under four minutes.

---

# PART I — CLOCKS

## 1. The geometry of the dial ⭐

| Fact | Value |
|---|---|
| Full dial | 360°, 12 hours, 60 minutes |
| **Each minute space** | **6°** (360/60) |
| **Each hour space** | **30°** (360/12) |
| **Minute hand speed** | **6° per minute** (one full round per hour) |
| **Hour hand speed** | **0.5° per minute** (30° per hour) |
| **Relative speed** (minute over hour) | **5.5° per minute** ⚡ |
| Minute hand gains on hour hand | **55 minute-spaces in 60 minutes** |

## 2. The angle formula ⭐⭐ (learn one, get everything)

**Angle between the hands at H hours M minutes = |30H − 5.5M|**

(If the result exceeds 180°, subtract it from 360° to get the acute/reflex answer the question wants.)

*Example:* at **3:40** → |30(3) − 5.5(40)| = |90 − 220| = 130°.

## 3. The standard events

| Event | Condition | Frequency |
|---|---|---|
| **Coincide** (0° apart, one over the other) | 30H = 5.5M | **11 times in 12 hours; 22 times a day** ⚠️ (not 24) |
| **Opposite** (180° apart, straight line) | |30H − 5.5M| = 180 | **11 times in 12 hours; 22 a day** |
| **Right angle** (90°) | |30H − 5.5M| = 90 | **22 times in 12 hours; 44 a day** |
| **In a straight line** (together *or* opposite) | 0° or 180° | 44 times a day |

⚡ **Why 11 and not 12:** the hands coincide every **720/11 = 65 5/11 minutes**, so in 720 minutes there are exactly **11** coincidences. The "missing" one is in the 11-o'clock hour: between 11:00 and 12:00 the hands meet only at **12:00 sharp**, which belongs to the next cycle. The same 11-in-12 logic gives 11 oppositions; right angles occur twice per cycle, hence 22 per 12 hours. **Exam fact: coincidence 11×, opposition 11×, right angle 22× per 12 hours — double each for a day.**

**Deriving a specific time ⚡:** to find when the hands coincide between H and H+1 o'clock, use
**M = (60H)/11 minutes past H** … for opposition, **M = (60/11)(H ± 6)**; for a 90° angle, **M = (60/11)(H ± 3)**.
*Between 4 and 5 they coincide at:* M = 240/11 = **21 9/11 minutes past 4**.

## 4. Faulty and mirror clocks

- **Gaining/losing clocks:** a clock that gains x minutes per day is *fast*; set up a proportion — "in 24 hours it gains x, so in T hours it gains xT/24". A clock showing the correct time again must have gained/lost a **full 12 hours (720 minutes)**.
- **Two clocks compared:** total relative error per day = gain of one + loss of the other; the time to differ by D minutes = D ÷ (relative error per day) days.
- **Mirror image of a clock ⚡:** mirror time = **11:60 − given time** (use 12:60 − time when the hour is 12 or minutes are 00). Mirror of 4:20 → 11:60 − 4:20 = **7:40**.
- **Water image of a clock:** 18:30 − given time (in 24-hour thinking), or simply reflect vertically — rarely asked; the mirror form is the common one.

---

# PART II — CALENDARS

## 5. Odd days — the whole chapter in one idea ⭐⭐

**"Odd days" = the remainder when a number of days is divided by 7.** Day-of-week questions are nothing but remainder arithmetic mod 7.

| Period | Odd days |
|---|---|
| **Ordinary year** (365 days) | **1** |
| **Leap year** (366 days) | **2** |
| **100 years** | **5** |
| **200 years** | **3** |
| **300 years** | **1** |
| **400 years** | **0** ⚡ (so the calendar repeats every 400 years) |

**Leap-year rule ⭐:** divisible by 4 → leap; **but century years must be divisible by 400**. So **1900 was not a leap year; 2000 was.** This is the single most-exploited fact in calendar questions.

**Month odd days (memorise the code):**

| Jan | Feb | Mar | Apr | May | Jun | Jul | Aug | Sep | Oct | Nov | Dec |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 3 | 0 (1 if leap) | 3 | 2 | 3 | 2 | 3 | 3 | 2 | 3 | 2 | 3 |

(31-day months give 3, 30-day months give 2, February gives 0 or 1.)

**Day codes:** 0 = **Sunday**, 1 = Monday, 2 = Tuesday, 3 = Wednesday, 4 = Thursday, 5 = Friday, 6 = Saturday.

### 5.1 The day-of-week procedure ⭐

To find the day for **d–m–y**:
1. **Century part:** take the completed centuries before the year. (e.g. for 2023, take 2000 → 2000 years = 5 × 400 → 0 odd days. For 1947, take 1900 = 1600 + 300 → 0 + 1 = 1 odd day.)
2. **Year part:** count the completed years after that century: odd days = (number of ordinary years × 1) + (number of leap years × 2) = **years + leap years**, taken mod 7.
3. **Month + date part:** add the month codes for the completed months of the target year, plus the given date.
4. Total mod 7 → map to the day code.

*Worked — 15 August 1947:*
- 1600 → 0; next 300 years → 1. Subtotal 1.
- 1901–1946 = 46 years, of which leap years = 11 (1904, 1908 … 1944). Odd days = 46 + 11 = 57 → 57 mod 7 = **1**. Subtotal 2.
- 1947 up to 15 Aug: Jan 31 + Feb 28 + Mar 31 + Apr 30 + May 31 + Jun 30 + Jul 31 + 15 = **227** days → 227 mod 7 = 3 (227 = 32×7 + 3). Total = 2 + 3 = **5 → Friday** ✔ (India's independence was indeed on a Friday.)

### 5.2 Repetition shortcuts ⚡

| Question | Answer |
|---|---|
| Same calendar repeats after | **6, 11 or 28 years** depending on the position in the leap cycle — the safe rule is: for an ordinary year add 6/11/11; a **leap year's calendar repeats after 28 years** |
| Day of the week after n days | (present day + n mod 7) |
| Day of the week n days *ago* | (present day − n mod 7) |
| 1st January of a year and 31st December | **same day** in an ordinary year; **different** in a leap year |
| The last day of a century | can only be **Monday, Wednesday, Friday or Sunday** — never Tuesday, Thursday or Saturday ⚡ |
| Number of leap years in 100 years | **24** (century year not a leap year) or 25 (if it is, e.g. 2000) |

---

# PART III — PROBLEMS ON AGES

## 6. The method

Ages questions are **linear equations in disguise**. Two disciplines solve all of them:

1. **Anchor on the present.** Let the present ages be x and y (or ratio terms 3k, 5k). Then:
 - "**n years ago**" → **subtract n from each**;
 - "**n years hence**" → **add n to each**.
 ⚠️ The commonest error is adding/subtracting from only one person, or applying the ratio to the past values directly.
2. **The difference is constant.** The gap between two people's ages **never changes**. If the ratio was 3 : 5 and is now 5 : 7, the difference (2k then, 2k now — with different k) gives you the equation immediately.

⚡ **Ratio shortcut:** if ages are in the ratio a : b now and will be c : d after n years, then
**x = a·n(c − d)/(ad − bc)** … in practice it is faster to write ak, bk and solve (ak + n)/(bk + n) = c/d.

## 7. Recurring templates

| Wording | Setup |
|---|---|
| "A is twice as old as B" | A = 2B |
| "A is twice as old as B **was** 10 years ago" | A = 2(B − 10) ⚠️ note the *was* |
| "The sum of the ages of A and B is…" | A + B = S |
| "The ratio of ages 5 years ago was 3 : 4 and 5 years hence will be 4 : 5" | (x−5)/(y−5) = 3/4 and (x+5)/(y+5) = 4/5 |
| "Father's age is three times the son's; after 10 years it will be twice" | F = 3S; F + 10 = 2(S + 10) |
| Average age of a family / group changes when someone joins | use the average rules from [File 03](03-Averages-Central-Tendencies-and-Alligation.md) |

⚡ **Option-substitution is legitimate and fast:** for a single-unknown age question, plug the four options into the *second* condition. It typically resolves in 20 seconds.

---

## 8. Worked PYQ-pattern set

**Q1.** The angle between the hands of a clock at 4:20 is:
**Sol.** |30(4) − 5.5(20)| = |120 − 110| = **10°**.

**Q2.** At what time between 3 and 4 o'clock do the hands coincide?
**Sol.** M = 60H/11 = 180/11 = **16 4/11 minutes past 3**.

**Q3.** How many times in a day are the hands of a clock at right angles?
**Sol.** **44 times.**

**Q4.** How many times in a day do the hands of a clock coincide?
**Sol.** **22 times** (11 per 12-hour cycle).

**Q5.** The mirror image of a clock showing 8:20 is:
**Sol.** 11:60 − 8:20 = **3:40**.

**Q6.** If 1 January 2024 is a Monday, what day is 1 January 2025?
**Sol.** 2024 is a leap year → 2 odd days → Monday + 2 = **Wednesday**.

**Q7.** What day of the week was 26 January 1950?
**Sol.** 1600 → 0; 300 more → 1. Years 1901–1949 = 49, leap years among them = 12 (1904…1948) → 49 + 12 = 61 → 61 mod 7 = 5. Subtotal 1 + 5 = 6. In 1950: Jan 26 → 26 mod 7 = 5. Total 6 + 5 = 11 → 11 mod 7 = **4 → Thursday** ✔ (the first Republic Day was a Thursday.)

**Q8.** How many leap years are there in 100 years (e.g. 1901–2000)?
**Sol.** 1904 to 2000 in steps of 4 → 25 candidates; 1900 is excluded from this range and 2000 **is** a leap year → **25**. For 1801–1900 the answer would be **24** (1900 is not a leap year). ⚠️ Always check the century year in the range.

**Q9.** A father is three times as old as his son. After 12 years he will be twice as old. The son's present age is:
**Sol.** 3S + 12 = 2(S + 12) → 3S + 12 = 2S + 24 → S = **12 years** (father 36).

**Q10.** The ratio of the present ages of A and B is 4 : 5. Six years ago it was 3 : 4. A's present age is:
**Sol.** (4k − 6)/(5k − 6) = 3/4 → 16k − 24 = 15k − 18 → k = 6 → A = **24 years**.

**Q11.** The sum of the ages of a mother and daughter is 60. Five years ago the mother was four times as old as the daughter. The daughter's present age is:
**Sol.** M = 60 − D. Condition: (M − 5) = 4(D − 5) → (55 − D) = 4D − 20 → 5D = 75 → D = **15 years** (mother 45; check five years ago: 40 = 4 × 10 ✔).

**Q12.** A clock gains 5 minutes every 24 hours. It is set right at 8 a.m. on Monday. What will it show at 8 p.m. on Tuesday?
**Sol.** Elapsed 36 hours → gain = 5 × 36/24 = 7.5 minutes → it shows **8:07:30 p.m.**

---

## 9. Traps checklist ⚠️

1. Hands coincide **22 times a day, not 24**; right angles **44 times**.
2. The **11:00–12:00 hour has no separate coincidence** — that is why the count is 11 per half-day.
3. Angle formula gives the raw value; if > 180°, subtract from 360°.
4. **1900 was not a leap year; 2000 was.** Century years need division by 400.
5. February's odd-day code changes to **1** in a leap year.
6. The last day of a century is never Tuesday, Thursday or Saturday.
7. In age problems, apply "n years ago/hence" to **every** person in the equation.
8. The **age difference is constant** — use it as a free equation.
9. Mirror-clock formula is **11:60 − time**, and the answer must still be a valid clock reading.
10. A gaining clock "shows the correct time again" only after **12 hours** of accumulated gain.

---

## 10. Rapid-fire recall

- **Angle = |30H − 5.5M|**; relative speed **5.5°/min**; coincidence every **65 5/11 min**.
- Coincide 22/day · Opposite 22/day · Right angle 44/day · Straight line 44/day.
- Coincidence time between H and H+1 = **60H/11 min past H**.
- Mirror clock = **11:60 − time**.
- Odd days: ordinary 1, leap 2, 100 yr 5, 200 yr 3, 300 yr 1, **400 yr 0**.
- Month codes: **3 0 3 2 3 2 3 3 2 3 2 3** (Feb = 1 in a leap year).
- Day code **0 = Sunday**.
- Leap-year calendar repeats after **28 years**.
- Ages: **difference is constant**; translate "ago/hence" to every term.

[← Series & Coding](06-Series-Coding-Decoding-Relations-and-Arrangements.md) · [Index](README.md) · [Next: Venn, Syllogism & Logical Reasoning →](08-Venn-Diagrams-Syllogisms-and-Logical-Reasoning.md)
