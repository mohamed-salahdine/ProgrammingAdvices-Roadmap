# 08 - Algorithms & Problem Solving Level 4 📅

**"Taming time: Building a Date Library from scratch."**

This directory contains the logic and implementation for a comprehensive **Date & Time Library**. Instead of relying on built-in types initially, I implemented the logic behind calendars, leap years, and date arithmetic manually to handle complex "Business Logic" scenarios.

## 🚀 Key Achievements
- **Leap Year Logic:** Correctly calculating leap years (divisible by 4, but not 100 unless by 400).
- **Date Arithmetic:**
  - Adding/Subtracting days to a date (handling month and year rollovers).
  - Calculating the difference (in days) between two dates.
  - Finding the "Day of the Week" for any given date (Zeller's congruence or reference date logic).
- **Validation:** Ensuring dates like `30/02/2023` are rejected immediately.
- **Utility Functions:**
  - `IsDate1AfterDate2`
  - `IsLastDayInMonth`
  - `DaysUntilEndOfWeek` / `DaysUntilEndOfYear`

## 📂 Project Context
This logic is the backbone for future enterprise applications (like the **Bank System**), where calculating interest rates, subscription expiries, and transaction timestamps requires absolute precision.

## 🧠 Why This Matters
Date bugs are infamous in software engineering (e.g., Y2K, Leap Year bugs). Writing this library taught me to respect **Edge Cases**—checking boundary conditions like the end of February or the transition from December 31st to January 1st.

## 🛠️ Stack
- **Language:** C++
- **Focus:** Business Logic & Temporal Algorithms.

---
## 🎓 Verification
[📄 **View Certificate of Completion (PDF)**](../../Certificates/08-certificate-of-completion-for-08-algorithms-problem-solving-level-4.pdf)