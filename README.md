--Description--
This Python script builds a series by concatenating numbers from 1 up to a user-provided value `n`. It then finds and reports which number contains the digit at a specified position (`pos`) within this concatenated series.

---Usage---
1. Run the script.
2. When prompted, input the last number `n` to consider in the series.
3. Input the digit position `pos` (1-based index).
4. The script outputs the entire concatenated series and indicates which number the digit at the selected position belongs to.

---Example---
Enter the last number to consider in the series: 15
Enter the digit position (1-based): 12
Series: 123456789101112131415
The digit at position 12 is part of number 11.


## How It Works
- The script iterates over numbers from 1 to `n`, converting each to a string and appending it to a series string.
- It tracks the cumulative length of this series.
- Once the cumulative length surpasses or equals the requested position, it identifies the number that contains the digit at the given position.
- It then prints out the series and the result.

## Limitations
- The position `pos` must be within the total length of the series (sum of the digits of all numbers from 1 to `n`).
- No error handling is implemented for invalid inputs (e.g., zero, negative numbers, or non-integers).

## Requirements
- Python 3.x

## Running
Run the script in any environment that supports Python 3.x by simply executing the script file.

---

This script is a straightforward demonstration of string manipulation and indexing in Python.

