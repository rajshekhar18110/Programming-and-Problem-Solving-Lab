
## Problem Statement
Write a Python program to perform union, intersection and difference operations on Set A and Set B.
---

## Algorithm
Step 1: Start
Step 2: Input day, month, year
Step 3: Check if year > 0 and month is between 1 and 12
  If not → Print "Invalid Date" and Stop
Step 4: Find maximum days in the given month
31 days → Jan, Mar, May, Jul, Aug, Oct, Dec
30 days → Apr, Jun, Sep, Nov
February → 28 days (29 if leap year)
Step 5: If day is not between 1 and max days → Print "Invalid Date" and Stop
Step 6: Increment date
If day < max days → day = day + 1
Else if month < 12 → day = 1, month = month + 1
Else → day = 1, month = 1, year = year + 1
Step 7: Print new date (DD-MM-YYYY)
Step 8: Stop
---

## Flowchart
![Flowchart](Set_Opp.drawio.png)

---

## Execution
<p align="center">
  <img src="Set_Opp.png" width="900">
</p>



