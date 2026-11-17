# Weekly Electricity Use

**Original program file:** `task .py88`

## 1. Aim
Calculate daily and weekly electricity consumption for a fridge, TV and fan, and check usage limits.

## 2. Algorithm
1. Start.
2. Set appliance names and days of the week.
3. Read the daily limit and weekly limit.
4. For each appliance, enter its units for all seven days.
5. Calculate and display each day's total usage.
6. If a daily total exceeds the daily limit, display a warning.
7. Calculate each appliance's weekly total.
8. If a weekly total exceeds the weekly limit, display a warning.
9. Stop.

## 3. Sample input
Daily limit 30; weekly limit 150; Fridge: 10,11,12,10,9,8,10; TV: 5,6,5,7,6,4,5; Fan: 8,9,10,11,12,10,9

## 4. Actual output (sample run)
```text
Weekly Electricity Use
Daily electricity limit (units): 30
Weekly limit per appliance (units): 150
Daily totals:
Mon: 23 units
Tue: 26 units
Wed: 27 units
Thu: 28 units
Fri: 27 units
Sat: 22 units
Sun: 24 units
Weekly totals:
Fridge: 70 units
TV: 38 units
Fan: 69 units
```

## 5. Conclusion
This program demonstrates lists, nested loops, totals and limit checking.

## Separate visual files
- [Flowchart](flowchart.svg)
- [Output screenshot](output-screenshot.svg)
