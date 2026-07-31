# 04 · Time & Work · Pipes & Cisterns · Time, Speed & Distance · Trains · Boats · Races

[← Averages](03-Averages-Central-Tendencies-and-Alligation.md) · [Index](README.md) · [Next: Mensuration & Non-Verbal →](05-Mensuration-Shapes-and-Non-Verbal-Reasoning.md)

**Syllabus phrases covered:** *"time and work, time and distance, speed and distance"*

**PYQ signal:** 4–6 questions. APPSC keeps the arithmetic clean and the story short: "A can do a work in 12 days, B in 18 days…", "A train 200 m long crosses a pole in 10 seconds…". Both halves of this chapter yield to **one habit each** — the **LCM method** for work and **relative speed** for motion. Learn those two and this chapter becomes free marks.

---

# PART I — TIME AND WORK

## 1. The LCM method ⚡⚡ (use it always)

Instead of fractions, **let the total work be the LCM of the given days**. Each worker's daily output then becomes a whole number.

*A does a job in 12 days, B in 18 days. Together?*
→ Total work = LCM(12, 18) = **36 units**. A = 36/12 = 3 units/day; B = 36/18 = 2 units/day → together 5 units/day → **36/5 = 7⅕ days**.

No fractions, no LCD, no errors. Every question below uses it.

### 1.1 Core relations

| Fact | Statement |
|---|---|
| Work rate | If A finishes in n days, A's one-day work = **1/n** |
| Combined | (A + B)'s one-day work = 1/a + 1/b → **together = ab/(a + b) days** ⚡ |
| Three together | 1/a + 1/b + 1/c → time = abc/(ab + bc + ca) |
| A alone from "A+B" data | 1/A = 1/(A+B) − 1/B → **A = (b × t)/(b − t)** where t = time together |
| Efficiency ∝ 1/time | If A is **twice as efficient** as B, A takes **half** the time; efficiency ratio 2 : 1 ⇒ time ratio 1 : 2 |
| Wages | Divided in the ratio of **work done** = ratio of **efficiencies** (if all work the same days) |

### 1.2 The chain rule (men–days–hours) ⭐

**(M₁ × D₁ × H₁) / W₁ = (M₂ × D₂ × H₂) / W₂**

Everything that helps (men, days, hours) multiplies on top; the work done sits below. This single equation answers all "if 15 men working 8 hours a day complete… then how many men…" questions.

### 1.3 Recurring patterns

1. **Alternate days:** A and B work on alternate days — compute the **2-day block** output, see how many full blocks fit, then finish the remainder. ⚠️ Always check **who starts**; the answer differs.
2. **Leaving mid-way:** A and B start together, A leaves after k days → subtract A's contribution and let B finish the rest.
3. **Efficiency comparison:** "A is 50% more efficient than B" → efficiency A : B = 3 : 2 → time A : B = **2 : 3**.
4. **Men, women, children equivalence:** convert everything into one unit (say, "man-units") before combining.
5. **Wages:** ₹X shared for a job → in the ratio of daily efficiencies × days worked.

---

## 2. Pipes and cisterns

Identical to time & work, with **outlet pipes taking a negative sign**.

- Inlet fills in a hours → +1/a per hour. Outlet empties in b hours → −1/b per hour.
- Both open: net = 1/a − 1/b; **the tank fills only if a < b**.
- **Leak problems:** "A pipe fills a tank in 6 h but takes 8 h due to a leak" → leak rate = 1/6 − 1/8 = 1/24 → the leak alone empties a full tank in **24 hours**.
- ⚠️ A pipe that "empties a *full* tank in b hours" and one that "can empty *the tank* in b hours" are the same; but if the tank is only part-full, scale accordingly.

---

# PART II — TIME, SPEED AND DISTANCE

## 3. The base

**Speed = Distance / Time** · Distance = Speed × Time · Time = Distance / Speed

### 3.1 Unit conversion ⚡
**km/h → m/s: multiply by 5/18.** **m/s → km/h: multiply by 18/5.**
(Remember 36 km/h = 10 m/s and 72 km/h = 20 m/s as anchors.)

### 3.2 Proportionality (the fast way to think)

- Distance fixed ⇒ **speed and time are inversely proportional**: if speed becomes a/b of the original, time becomes **b/a** of the original.
- ⚡ **Late/early template:** walking at 4 km/h a man is 5 min late; at 5 km/h he is 10 min early. Speeds 4 : 5 ⇒ times 5 : 4 ⇒ the 1-part difference equals 15 min ⇒ times are 75 and 60 min ⇒ distance = 4 × (75/60) = **5 km**.
- **Two speeds, two arrival differences** (general): D = (S₁S₂/(S₂ − S₁)) × (total time difference in hours).

### 3.3 Average speed ⭐

| Case | Average speed |
|---|---|
| Equal **distances** at x and y | **2xy/(x + y)** (harmonic mean) |
| Equal distances at x, y, z | 3xyz/(xy + yz + zx) |
| Equal **times** at x and y | **(x + y)/2** |
| General | **total distance ÷ total time** — always safe |

⚠️ "Goes at 30 and returns at 60" → **40 km/h**, never 45.

### 3.4 Relative speed ⭐⭐

| Direction | Relative speed |
|---|---|
| **Opposite** (approaching / crossing) | **u + v** |
| **Same** (overtaking) | **u − v** |

Time to meet = (initial gap) / (relative speed). This one row solves trains, boats, races and "two men walking towards each other" alike.

---

## 4. Trains ⭐

The only extra idea: **a train has length**, so the distance covered in "crossing" includes it.

| Event | Distance covered |
|---|---|
| Crossing a **pole / man / signal post / tree** | **length of the train** |
| Crossing a **platform / bridge / tunnel** | **train + platform** |
| Two trains crossing each other | **sum of the two lengths** (at relative speed) |
| Train overtaking a man walking | train's length, at **relative** speed |

⚡ **Ratio shortcut:** if two trains of lengths L₁, L₂ cross a pole in t₁, t₂ seconds, then crossing each other takes **(L₁ + L₂)/(v₁ ± v₂)** where v = L/t.

⚡ **The classic:** two trains start towards each other from A and B and reach B and A in a and b hours after meeting → **speed ratio = √b : √a**.

---

## 5. Boats and streams ⭐

Let boat speed in still water = **b**, stream speed = **s**.

- **Downstream speed = b + s** · **Upstream speed = b − s**
- **b = (down + up)/2** · **s = (down − up)/2** ⚡ (memorise this pair; most questions are just this)
- If a boat takes the **same time** to go D₁ downstream and D₂ upstream: D₁/(b+s) = D₂/(b−s).
- Round trip over distance D: total time = D/(b+s) + D/(b−s); average speed = **(b² − s²)/b**.
- ⚠️ In still water, "the boat's speed" is b — do not average downstream and upstream *times*.

---

## 6. Races and circular tracks

- **"A beats B by x metres"** in a race of d metres: when A finishes d, B has run (d − x).
- **"A beats B by t seconds":** B's time − A's time = t.
- **"A gives B a start of x metres":** A runs d, B runs (d − x).
- **Dead heat** = both finish together.
- **Circular track, two runners from the same point:**
 - Time to meet **anywhere** = circumference / (u + v) for opposite directions, / |u − v| for the same direction.
 - Time to meet **at the starting point** = **LCM of (C/u, C/v)**.

---

## 7. Worked PYQ-pattern set

**Q1.** A can do a piece of work in 15 days and B in 20 days. Working together, they finish it in:
**Sol.** LCM = 60 units; A = 4, B = 3 → 7/day → **60/7 = 8⁴/₇ days**. (Or ab/(a+b) = 300/35.)

**Q2.** A and B together can do a work in 8 days; A alone in 12 days. B alone takes:
**Sol.** LCM(8, 12) = 24; together = 3, A = 2 → B = 1 → **24 days**.

**Q3.** A is twice as good a workman as B, and together they finish a job in 14 days. A alone takes:
**Sol.** Efficiency A : B = 2 : 1 → total 3 parts → A alone = 14 × 3/2 = **21 days**.

**Q4.** 12 men can complete a work in 18 days. How many men are needed to finish it in 8 days?
**Sol.** M₁D₁ = M₂D₂ → 12 × 18 = M × 8 → **27 men**.

**Q5.** A can do a work in 10 days, B in 15. They start together but A leaves after 2 days. B finishes the rest in:
**Sol.** LCM = 30; A = 3, B = 2. First 2 days: 2 × 5 = 10 units. Remaining 20 → B needs 20/2 = **10 days**.

**Q6.** Two pipes fill a tank in 12 and 15 hours; an outlet empties it in 20 hours. With all three open, the tank fills in:
**Sol.** LCM = 60; +5 +4 −3 = 6/hour → **10 hours**.

**Q7.** A train 180 m long running at 54 km/h crosses a platform 270 m long in:
**Sol.** 54 km/h = 15 m/s; distance = 450 m → **30 seconds**.

**Q8.** Two trains 120 m and 180 m long run in opposite directions at 45 and 63 km/h. Time to cross each other:
**Sol.** Relative speed = 108 km/h = 30 m/s; distance = 300 m → **10 seconds**.

**Q9.** A man rows 30 km downstream in 3 hours and returns in 5 hours. His speed in still water is:
**Sol.** Down = 10 km/h, up = 6 km/h → b = (10 + 6)/2 = **8 km/h** (stream = 2 km/h).

**Q10.** Walking at ¾ of his usual speed, a man reaches office 20 minutes late. His usual time is:
**Sol.** Speed ratio 3 : 4 ⇒ time ratio 4 : 3 ⇒ the extra 1 part = 20 min ⇒ usual time = 3 parts = **60 minutes**.

**Q11.** In a 500 m race, A beats B by 50 m. If they run at the same speeds in a 1000 m race, A beats B by:
**Sol.** B covers 450 when A covers 500 → ratio 10 : 9 → in 1000 m, B covers 900 → A wins by **100 m**.

**Q12.** Two runners on a 400 m circular track run at 5 m/s and 3 m/s in the same direction. They meet again after:
**Sol.** Relative speed 2 m/s → 400/2 = **200 seconds**.

---

## 8. Traps checklist ⚠️

1. **Crossing a pole = train length only; crossing a platform = train + platform.** The commonest single error in the chapter.
2. Average speed for a there-and-back trip is the **harmonic** mean, never the arithmetic mean.
3. **km/h ↔ m/s** — forgetting 5/18 turns a right method into a wrong answer.
4. Alternate-day work: **who starts first** changes the answer.
5. Outlet pipes are **negative**; check whether the tank can fill at all.
6. "A is 50% more efficient" → time ratio **2 : 3**, not 3 : 2. Efficiency and time are inverses.
7. Boats: still-water speed is the **average of the speeds**, not of the times.
8. Races: "beats by 50 m" fixes a **distance ratio**, which then scales to any race length.
9. Chain rule: keep work (W) on the correct side; if the second job is twice as large, W₂ = 2W₁.
10. Circular track: "meet anywhere" ≠ "meet at the starting point" (the latter is an **LCM**).

---

## 9. Rapid-fire recall

- Together: **ab/(a + b)** days. Chain rule: **M₁D₁H₁/W₁ = M₂D₂H₂/W₂**.
- Efficiency ∝ 1/time; wages ∝ work done.
- Leak: 1/fill − 1/actual = leak rate.
- **km/h × 5/18 = m/s.**
- Distance fixed ⇒ speed : time inverse. Speeds a : b ⇒ times b : a.
- **Average speed = 2xy/(x + y)** for equal distances.
- Relative speed: **u + v** opposite, **u − v** same direction.
- Trains meeting then reaching in a and b hours ⇒ **speed ratio √b : √a**.
- Boat: **b = (d + u)/2, s = (d − u)/2**.
- Circular, same start point: **LCM of lap times**.

[← Averages](03-Averages-Central-Tendencies-and-Alligation.md) · [Index](README.md) · [Next: Mensuration & Non-Verbal →](05-Mensuration-Shapes-and-Non-Verbal-Reasoning.md)
