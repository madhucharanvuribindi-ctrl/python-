# Hostel Resource Report

**Original program file:** `task.py11`

## 1. Aim
Calculate room charges and floor-wise electricity and water usage.

## 2. Algorithm
1. Start.
2. Store electricity and water readings for each room.
3. Set electricity and water rates and usage limits.
4. For each floor, set electricity and water totals to zero.
5. For each room, calculate its charge.
6. Check whether the room exceeds either usage limit.
7. Add room readings to the floor totals.
8. Display floor totals and save them.
9. Find the floors with the highest electricity and water usage.
10. Display the report.
11. Stop.

## 3. Sample input
The program uses the student and price data already stored in the program. The sample output below follows those values.

## 4. Actual output (sample run)
```text
Hostel Resource Report
Floor 1
Room 1 charge: Rs. 1120
Room 2 charge: Rs. 1400
Floor electricity: 270 units
Floor water: 180 units
Floor 2
Room 1 charge: Rs. 860
Room 2 charge: Rs. 1680
Electricity limit exceeded.
Water limit exceeded.
Floor electricity: 270 units
Floor water: 190 units
Floor with most electricity: 1
Floor with most water: 2
```

## 5. Conclusion
This program demonstrates nested lists, nested loops, totals and maximum-value selection.

## Separate visual files
- [Flowchart](flowchart.svg)
- [Output screenshot](output-screenshot.svg)
