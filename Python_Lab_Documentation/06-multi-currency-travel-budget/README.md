# Multi-Currency Travel Budget Analysis

**Original program file:** `task.py44`

## 1. Aim
Convert travel expenses into rupees, include a conversion fee and compare spending with a budget.

## 2. Algorithm
1. Start.
2. Store exchange rates, conversion fee and travel budget.
3. Store expenses with category, currency and amount.
4. For each expense, convert its amount into rupees.
5. Calculate the conversion fee and add it to the converted amount.
6. Add the final amount to total spending and its category total.
7. Display each converted expense.
8. Compare total spending with the budget.
9. Find the category with the largest total.
10. Display the budget result and largest category.
11. Stop.

## 3. Sample input
The program uses the student and price data already stored in the program. The sample output below follows those values.

## 4. Actual output (sample run)
```text
Hotel : USD 200 = 16932.0 rupees
Food : EUR 80 = 7344.0 rupees
Transport : INR 5000 = 5100.0 rupees
Food : USD 40 = 3386.4 rupees
Activities : EUR 50 = 4590.0 rupees
Total spending: 37352.4 rupees
Within budget. Remaining: 12647.6 rupees
Largest expense category: Hotel
```

## 5. Conclusion
This program demonstrates dictionaries, tuples, currency conversion and budget analysis.

## Separate visual files
- [Flowchart](flowchart.svg)
- [Output screenshot](output-screenshot.svg)
