📘 JavaScript Assignment 4 – Fundamentals of Web Design

👨‍💻 Student Details

- Name: Sangam kumar yadav
- Course: CSE 106 – Fundamentals of Web Design
- Assignment: Assignment 4
- Repository Name: JS-Assignment

---

📌 Overview

This assignment consists of 6 problem statements implemented using plain JavaScript.
All programs follow the constraints:

- Input is taken using "prompt()"
- Output is displayed using "alert()"
- No hardcoding is used
- Logic is implemented using concepts covered in class

---

🧠 Approach & Logic

🔹 Question 1: Digit Gatekeeper

- Iterate from "L" to "R"
- Check:
  - Divisible by "K"
  - No digit is "0"
  - Sum of digits is prime
- Use helper function for prime checking
- Time Complexity: O(N × d)
  (N = range, d = number of digits)

---

🔹 Question 2: Roll-Seed Lock

- Apply transformation 3 times:
  - Even → "n/2 + seed"
  - Odd → "n*3 - seed"
- Check:
  - Number is 3-digit
  - Middle digit equals seed
- Time Complexity: O(1)

---

🔹 Question 3: Mirror Corridor

- Loop "X" from "0 → 100000"
- Check:
  - "(N + X)" is palindrome
  - Divisible by "K"
- Return smallest valid "X"
- Time Complexity: O(N × d)

---

🔹 Question 4: Fare Calculator

- Apply fare rules step-by-step:
  1. Base calculation
  2. Late penalty
  3. Distance bonus
  4. Seed adjustment
  5. Round up to nearest multiple of 5
- Time Complexity: O(1)

---

🔹 Question 5: Skipping Numbers

- Keep adding numbers from 1 onward
- Skip numbers divisible by "(seed + 2)"
- Stop when sum ≥ N
- Time Complexity: O(m)

---

🔹 Question 6: Contest Score Judge

- Calculate score: "3a + b - 2c"
- Apply conditions:
  - Negative → 0
  - If total attempts > 50 → subtract 10
- Decide PASS / FAIL
- Time Complexity: O(1)

---

📂 File Structure

JS-Assignment/
│── q1.js
│── q2.js
│── q3.js
│── q4.js
│── q5.js
│── q6.js
│── README.md

---

✅ Key Concepts Used

- Loops ("for", "while")
- Conditional statements ("if-else")
- Functions
- Number manipulation
- String operations
- Math functions ("Math.floor", "Math.ceil")

---

🚀 Conclusion

This assignment demonstrates problem-solving using JavaScript fundamentals.
Each problem is solved efficiently with clear logic and proper handling of edge cases.

---
