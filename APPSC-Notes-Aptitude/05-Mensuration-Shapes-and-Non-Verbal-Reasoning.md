# 05 · Mensuration · "Shapes and their Sub-sections" · Non-Verbal Reasoning (Figures, Dice, Cubes)

[← Time, Work, Speed](04-Time-Work-Speed-and-Distance.md) · [Index](README.md) · [Next: Series, Coding & Arrangements →](06-Series-Coding-Decoding-Relations-and-Arrangements.md)

**Syllabus phrases covered:** *"shapes and their sub-sections"*, *"area and perimeter of simple geometrical shapes, volume and surface area of sphere, cone, cylinder, cubes and cuboids"*

**PYQ signal:** two distinct sub-blocks.
1. **Mensuration** — pure formula recall, 3–5 questions. If you know the formula the question takes 40 seconds; if you don't, it is unanswerable. **So the formulae are non-negotiable.**
2. **"Shapes and their sub-sections"** — this is APPSC's phrase for **non-verbal / spatial reasoning**: counting figures, paper folding & cutting, mirror and water images, embedded and completion figures, dice and painted cubes. Confirmed as recurring in APPSC reasoning sets.

---

# PART I — MENSURATION

## 1. Two-dimensional figures ⭐

| Figure | Area | Perimeter |
|---|---|---|
| **Square** (side a) | **a²** (= d²/2) | 4a; diagonal **a√2** |
| **Rectangle** (l, b) | **lb** | 2(l + b); diagonal √(l² + b²) |
| **Triangle** | **½ × base × height** | a + b + c |
| Triangle (3 sides) | **Heron: √[s(s−a)(s−b)(s−c)]**, s = (a+b+c)/2 | — |
| **Equilateral triangle** (a) | **(√3/4)a²**; height **(√3/2)a** | 3a |
| **Right triangle** | ½ × product of the legs | Pythagoras: h² = p² + b² |
| **Parallelogram** | base × height | 2(a + b) |
| **Rhombus** | **½ d₁d₂** | 4a; d₁² + d₂² = 4a² |
| **Trapezium** | **½ (sum of parallel sides) × height** | sum of all sides |
| **Circle** (r) | **πr²** | **2πr** |
| **Sector** (angle θ) | **(θ/360)πr²** | arc = (θ/360)2πr |
| **Ring/annulus** | π(R² − r²) | — |
| **Regular polygon (n sides)** | interior angle = **(n−2)180/n**; sum of interior angles = (n−2)×180°; **sum of exterior angles = 360° always** | — |

**Pythagorean triples worth knowing ⚡:** 3-4-5, 5-12-13, 8-15-17, 7-24-25, 9-40-41 (and all multiples). Spotting one saves a square-root computation.

## 2. Three-dimensional solids ⭐⭐ (the syllabus names these explicitly)

| Solid | Volume | Curved / Lateral SA | Total SA |
|---|---|---|---|
| **Cube** (a) | **a³** | 4a² | **6a²** · diagonal **a√3** |
| **Cuboid** (l, b, h) | **lbh** | 2h(l + b) | **2(lb + bh + hl)** · diagonal **√(l²+b²+h²)** |
| **Cylinder** (r, h) | **πr²h** | **2πrh** | **2πr(r + h)** |
| **Cone** (r, h, slant l) | **⅓πr²h** | **πrl** | **πr(r + l)** · **l = √(r² + h²)** |
| **Sphere** (r) | **(4/3)πr³** | — | **4πr²** |
| **Hemisphere** | **(2/3)πr³** | 2πr² | **3πr²** |
| **Prism** | base area × height | perimeter × height | 2(base) + lateral |
| **Pyramid** | ⅓ × base area × height | ½ × perimeter × slant height | base + lateral |

**Relations examiners like ⚡**
- Cone : hemisphere : cylinder of the **same radius and height** have volumes in the ratio **1 : 2 : 3**.
- The **largest sphere carved from a cube** of side a has r = a/2 → volume ratio sphere : cube = **π : 6**.
- A sphere melted and recast into smaller spheres/cylinders → **volume is conserved**; equate volumes.

### 2.1 The scaling law ⭐ (answers many questions instantly)
If every linear dimension is multiplied by **k**:
- **Length × k**, **Area × k²**, **Volume × k³**.

⚡ So "if the radius of a sphere is doubled, its surface area becomes 4× and volume 8×" needs no formula at all. Similarly, a 10% rise in the side of a cube raises the volume by 1.1³ − 1 = **33.1%**.

### 2.2 Standard word-problem shapes
- **Room painting / whitewashing:** four walls = 2h(l + b); add ceiling if stated, **never** the floor.
- **Cost problems:** cost = area × rate — check whether the rate is per m² or per m.
- **Path around/inside a rectangle:** outer area − inner area; a path of width w *outside* gives (l + 2w)(b + 2w) − lb.
- **Water flow into a tank:** volume delivered = cross-section area of pipe × speed × time.
- **Roller:** area covered in one revolution = curved surface area of the cylinder = 2πrh.

---

# PART II — "SHAPES AND THEIR SUB-SECTIONS" (NON-VERBAL REASONING)

## 3. Counting of figures ⭐

**The systematic method — never count at random:**
1. Label every distinct region/vertex in the figure.
2. Count figures made of **1 component**, then **2 components**, then **3**, … and add.
3. Cross-check with a known formula where the figure is regular.

**Formulae for standard constructions ⚡**

| Construction | Count |
|---|---|
| Squares in an **n × n** grid | 1² + 2² + … + n² = **n(n+1)(2n+1)/6** |
| Rectangles in an **n × n** grid | (1 + 2 + … + n)² = **[n(n+1)/2]²** |
| Rectangles in an **m × n** grid | **[m(m+1)/2] × [n(n+1)/2]** |
| Triangles in a triangle divided by n cevians from one vertex | n(n+1)/2 |
| Straight lines through n points, no three collinear | ⁿC₂ |
| Diagonals of an n-sided polygon | **n(n − 3)/2** |

*Example:* a 4 × 4 chessboard-style grid contains 4(5)(9)/6 = **30 squares** and [4·5/2]² = **100 rectangles**.

⚠️ "Rectangles" **includes** squares unless the question says "rectangles which are not squares".

## 4. Paper folding and cutting ⭐

**The rule: unfold in reverse order, and each fold acts as a mirror.**

- One fold → the cut is reflected once → **2 holes** (unless the cut is on the fold line, which gives 1).
- Two folds → **4** symmetric holes; three folds → 8.
- A cut **on the crease** produces a **half-shape that opens into a full symmetric shape** (a semicircle on the fold opens into a circle).
- ⚡ **Fast elimination:** check (i) the **number** of holes, (ii) their **symmetry about each crease**, (iii) the **shape** (a triangle notch at a corner opens into a diamond). Two of these three usually kill three options.

**Paper cutting (patterns) and completion of figures** follow the same logic: look for the **axis of symmetry** first.

## 5. Mirror and water images ⭐

| Image | Rule |
|---|---|
| **Mirror image** (vertical mirror on the right/left) | **left ↔ right** reversal; the order of letters reverses |
| **Water image** (mirror below) | **top ↔ bottom** reversal |

**Letters unchanged in a mirror image (vertically symmetric):** **A, H, I, M, O, T, U, V, W, X, Y** (and digits 0, 8 — approximately).
**Letters unchanged in a water image (horizontally symmetric):** **B, C, D, E, H, I, K, O, X** (and digits 0, 1, 3, 8).

⚡ For a word, the mirror image is the word **written in reverse order**, each letter itself flipped. So a question asking for the mirror image of "MOTOR" gives you "ROTOM" with each letter flipped — and since M, O, T are symmetric, only R changes shape.

## 6. Embedded, hidden and completion figures
- **Embedded figure:** the answer must contain the given figure **in the same orientation and proportion** — rotation is *not* allowed unless the question says so. Trace the outline of the key shape and hunt for it.
- **Figure completion / series:** identify the **rule of change** — rotation (by how many degrees, which direction), addition/removal of elements, shading movement, mirroring. Track **one element at a time** across the sequence rather than the whole figure.
- **Rotation convention:** clockwise 90° sends "up" to "right". Most series use a constant 45°, 90° or 180° step.

## 7. Dice ⭐

**Rules:**
1. A cube has 3 pairs of opposite faces; **opposite faces are never adjacent** — the core of every dice question.
2. **Standard dice:** the sum of opposite faces is **7** (1-6, 2-5, 3-4).
3. **Two positions of the same die:** if **one face is common** to both views, the remaining faces of the two views are all adjacent to it; the two faces that are *not* common and not visible together are opposite.
4. If **two faces are common** and in the **same position**, the other two faces are opposite; if the common faces have moved (rotated), rotate the die mentally in the same sense.
5. **Ordinary dice** (non-standard): opposite pairs must be deduced purely from adjacency.

⚡ **Adjacency method** (fastest and most reliable): list every face seen *together with* a given face — those are all adjacent to it. The one face never seen with it is **opposite** to it.

## 8. Cubes and painted cubes ⭐

A cube painted on all faces and cut into **n³** smaller cubes of equal size:

| Small cubes with | Count |
|---|---|
| **3 faces painted** (corners) | **8** — always |
| **2 faces painted** (edges) | **12(n − 2)** |
| **1 face painted** (face centres) | **6(n − 2)²** |
| **0 faces painted** (interior) | **(n − 2)³** |
| Total | n³ |

*Check:* 8 + 12(n−2) + 6(n−2)² + (n−2)³ = n³ ✔

⚡ For n = 4: 8, 24, 24, 8 (total 64). For n = 5: 8, 36, 54, 27 (total 125). Memorising these two rows covers most questions.

**Variants:**
- Only some faces painted (e.g. two opposite faces red, rest green) → recount using the same corner/edge/face logic, face by face.
- **Cut into unequal pieces:** the question will give the number of cuts along each axis — pieces = (x+1)(y+1)(z+1).
- **Minimum cuts to make n³ cubes** = 3(n − 1).

---

## 9. Worked PYQ-pattern set

**Q1.** The volume of a sphere is 36π cm³. Its surface area is:
**Sol.** (4/3)πr³ = 36π → r³ = 27 → r = 3 → SA = 4π(9) = **36π cm²**.

**Q2.** The radius of a cylinder is doubled and the height halved. The new volume is:
**Sol.** πr²h → π(2r)²(h/2) = 2πr²h → **twice the original**.

**Q3.** The diagonal of a cube is 6√3 cm. Its volume is:
**Sol.** a√3 = 6√3 → a = 6 → **216 cm³**.

**Q4.** A cone and a cylinder have the same radius and height. The ratio of their volumes is:
**Sol.** **1 : 3**.

**Q5.** The area of an equilateral triangle of side 8 cm is:
**Sol.** (√3/4)(64) = **16√3 cm²**.

**Q6.** How many squares are there in a 5 × 5 grid?
**Sol.** 5(6)(11)/6 = **55**.

**Q7.** A cube of side 4 cm is painted on all faces and cut into 1 cm cubes. How many have exactly two faces painted?
**Sol.** 12(n − 2) = 12 × 2 = **24**.

**Q8.** How many diagonals does a decagon have?
**Sol.** n(n−3)/2 = 10 × 7/2 = **35**.

**Q9.** A die shows 1, 2, 3 in one view and 3, 4, 5 in another (3 common in both). Which number is opposite 3?
**Sol.** 1, 2, 4, 5 are all adjacent to 3 → the remaining face, **6**, is opposite 3.

**Q10.** A square sheet is folded twice (left over right, then top over bottom) and a small circle is punched near the centre of the folded corner region. On unfolding, the number of holes is:
**Sol.** Two folds → **4 holes**, symmetric about both creases.

**Q11.** The mirror image of the word **"COURT"** placed before a vertical mirror reads:
**Sol.** Letter order reverses → **TRUOC**, with each letter laterally inverted (C, O, U, T look reversed; R clearly so).

**Q12.** The curved surface area of a cone with radius 7 cm and height 24 cm is:
**Sol.** l = √(49 + 576) = 25 → πrl = (22/7)(7)(25) = **550 cm²**.

---

## 10. Traps checklist ⚠️

1. **Total** surface area vs **curved/lateral** surface area — read which is asked (cylinder: 2πrh vs 2πr(r+h)).
2. Cone: use the **slant height l** in πrl, not the vertical height.
3. Hemisphere **total** SA is **3πr²** (curved 2πr² + flat circle πr²), not 2πr².
4. Scaling: volume goes as **k³**, area as k², so "doubling the radius doubles the volume" is always wrong.
5. Four walls of a room exclude the floor and (usually) the ceiling.
6. Counting figures: "rectangles" includes squares; "triangles" includes the big outer triangle.
7. Painted cubes: **8 corner cubes always**, regardless of n.
8. Dice: opposite faces are those **never seen together**; sum 7 applies only to a *standard* die.
9. Mirror image reverses **order**, water image reverses **vertically** — do not mix them.
10. Embedded figures must be found **without rotation**.

---

## 11. Rapid-fire recall

- Cube: **a³, 6a², a√3**. Cuboid diagonal: **√(l²+b²+h²)**.
- Cylinder **πr²h / 2πrh**; cone **⅓πr²h / πrl**, l = √(r²+h²); sphere **(4/3)πr³ / 4πr²**; hemisphere **(2/3)πr³ / 3πr²**.
- Cone : hemisphere : cylinder (same r, h) = **1 : 2 : 3**.
- Linear k ⇒ area k² ⇒ volume k³.
- Equilateral: **(√3/4)a²**. Rhombus: **½d₁d₂**. Trapezium: **½(a+b)h**.
- Polygon: diagonals **n(n−3)/2**; exterior angles sum **360°**.
- Grid: squares **n(n+1)(2n+1)/6**; rectangles **[n(n+1)/2]²**.
- Painted cube: **8 / 12(n−2) / 6(n−2)² / (n−2)³**.
- Standard dice: opposite faces sum to **7**.
- Mirror-safe letters: **A H I M O T U V W X Y**.

[← Time, Work, Speed](04-Time-Work-Speed-and-Distance.md) · [Index](README.md) · [Next: Series, Coding & Arrangements →](06-Series-Coding-Decoding-Relations-and-Arrangements.md)
