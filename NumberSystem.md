# 🔢 DIVISIBILITY, HCF & LCM

### *(Indian Hi-Tech Company Aptitude – Simple & Scoring Method)*

---

## 1️⃣ DIVISIBILITY – FAST CHECK METHOD

### ✔ Divisibility by **3**

**Technique:** Add digits → if sum divisible by 3 → number divisible

**Example:**
Number = **453**
4 + 5 + 3 = **12** → divisible by 3
✅ **453 is divisible by 3**

📝 **NOTE:** Same rule applies for **9**

---

### ✔ Divisibility by **4**

**Technique:** Check **last 2 digits** only

**Example:**
Number = **2316**
Last 2 digits = **16** → divisible by 4
✅ **Number divisible by 4**

📝 **NOTE:** Ignore all digits except last 2

---

### ✔ Divisibility by **8**

**Technique:** Check **last 3 digits** only

**Example:**
Number = **56024**
Last 3 digits = **024 = 24** → divisible by 8
✅ **Divisible**

📝 **NOTE:** Remaining digits don’t matter

---

### ✔ Divisibility by **11**

**Technique:**
(Sum of digits in odd places − sum of digits in even places)

**Example:**
Number = **121**
(1 + 1) − 2 = **0** → divisible by 11
✅ **Yes**

---

## 2️⃣ HCF (Highest Common Factor)

### 🔹 METHOD 1: PRIME FACTORIZATION *(Small numbers)*

**Steps:**
1️⃣ Factorize numbers
2️⃣ Take **common factors with smallest power**

**Example:** Find HCF of **36 and 48**

```
36 = 2² × 3²
48 = 2⁴ × 3
```

Common = **2² × 3**
👉 **HCF = 12**

📝 **NOTE:**
• Smallest power only
• Common primes only

---

### 🔹 METHOD 2: EUCLIDEAN METHOD *(Most Important)*

**Steps:**
1️⃣ Divide larger by smaller
2️⃣ Continue till remainder = 0
3️⃣ Last divisor = **HCF**

**Example:** Find HCF of **180 and 48**

```
180 = 48 × 3 + 36
48  = 36 × 1 + 12
36  = 12 × 3 + 0
```

👉 **HCF = 12**

📝 **NOTE:**
• Best for large numbers
• Very common in exams

---

## 3️⃣ LCM (Least Common Multiple)

### 🔹 METHOD 1: FORMULA METHOD *(Fastest)*

**Formula:**
**LCM × HCF = Product of numbers**

**Example:** Find LCM of **12 and 18**
HCF = **6**

```
LCM = (12 × 18) ÷ 6 = 36
```

📝 **NOTE:**
• Find HCF first
• One-line calculation

---

### 🔹 METHOD 2: PRIME FACTORIZATION

**Steps:**
1️⃣ Write prime factors
2️⃣ Take **highest power of each prime**

**Example:** Find LCM of **24 and 36**

```
24 = 2³ × 3
36 = 2² × 3²
```

LCM = **2³ × 3² = 72**

📝 **NOTE:**
• Highest power matters
• Include all primes

---

## 4️⃣ MOST IMPORTANT APTITUDE QUESTIONS

### 🔹 TYPE 1: Same Remainder Problems

**Technique:** Take **differences → find HCF**

**Example:** Find greatest number dividing **52, 72, 108** leaving same remainder

```
72 − 52 = 20
108 − 72 = 36
HCF(20, 36) = 4
```

👉 **Answer = 4**

📝 **NOTE:** Same remainder → **HCF of differences**

---

### 🔹 TYPE 2: Smallest Number Divisible

**Technique:** Find **LCM**

**Example:** Smallest number divisible by **6, 8, 15**

```
LCM = 2³ × 3 × 5 = 120
```

---

### 🔹 TYPE 3: Fraction Simplification

**Technique:** Divide numerator & denominator by **HCF**

**Example:** Simplify **168 / 216**

```
HCF = 24
168 ÷ 24 = 7
216 ÷ 24 = 9
```

👉 **Answer = 7/9**

---

### 🔹 TYPE 4: Given HCF & LCM

**Formula:**
**Product = HCF × LCM**

**Example:**
HCF = **8**, LCM = **240**
One number = **40**

```
Other number = (8 × 240) ÷ 40 = 48
```

📝 **NOTE:** Direct substitution – very common

---

### 🔹 TYPE 5: Bells / Lamps / Machines

**Technique:** Find **LCM of time intervals**

**Example:** Bells ring every **6, 10, 15 seconds**
👉 Ring together after **LCM = 30 seconds**

---

## 5️⃣ SUPER SHORTCUT NOTES (REVISION)

📝 **EXAM NOTES**

* Even & odd numbers → **HCF = 1**
* One number divides another → **HCF = smaller**
* Consecutive numbers → **HCF = 1**
* LCM of consecutive numbers → **Product**
* Same remainder → **HCF of differences**
* Together / simultaneously → **LCM**

---
