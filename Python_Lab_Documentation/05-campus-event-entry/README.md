# Campus Event Entry

**Original program file:** `task.py14`

## 1. Aim
Validate event tickets, prevent duplicate entries and allocate seats.

## 2. Algorithm
1. Start.
2. Create the seating arrangement and registered-ticket list.
3. Read each ticket ID.
4. If the ID is not registered, report an invalid ticket.
5. If the ID was already used, report a duplicate entry.
6. Otherwise, find the first empty seat and assign the ticket.
7. If no empty seat exists, report that no seats are available.
8. Count all remaining empty seats.
9. Display the available seats and seating plan.
10. Stop.

## 3. Sample input
The program uses the student and price data already stored in the program. The sample output below follows those values.

## 4. Actual output (sample run)
```text
Campus Event Entry
A101 - Allowed, row 1 seat 1
A102 - Allowed, row 1 seat 2
A101 - Duplicate entry
X999 - Invalid ticket
A104 - Allowed, row 1 seat 3
Available seats: 3
Seating plan:
['A101', 'A102', 'A104']
['Empty', 'Empty', 'Empty']
```

## 5. Conclusion
This program demonstrates list searching, nested loops, conditions and seat allocation.

## Separate visual files
- [Flowchart](flowchart.svg)
- [Output screenshot](output-screenshot.svg)
