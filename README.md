# DAY-3: Student Performance Analyzer

## Project Overview
This Python program analyzes student internal assessment marks.  
It stores the marks in a list and processes them using a for loop.  
Each student is classified into a performance category, and a final summary is displayed.

---

## Objectives
- Use list to store multiple marks  
- Use for loop for processing  
- Use conditional statements for classification  
- Avoid built-in functions like max(), min(), sum()  
- Implement personalized logic  

---

## Personalized Logic
The program calculates the sum of the last two digits of my roll number.  
This value is added as grace marks (only if the total does not exceed 100) before classification.  
This personalized rule changes the final output and makes the program unique.

---

## Classification Criteria

| Marks Range | Category     |
|-------------|-------------|
| 90 – 100    | Excellent   |
| 75 – 89     | Very Good   |
| 60 – 74     | Good        |
| 40 – 59     | Average     |
| 0 – 39      | Fail        |
| <0 or >100  | Invalid     |

---
