# NaturalNumber Root Calculator

## Description
This program computes the `r`-th root of a given natural number using the **interval halving method**. It uses the `NaturalNumber` class and demonstrates the implementation of an efficient algorithm for function inversion.

## Objectives
- Familiarity with `NaturalNumber` objects and their methods.
- Understanding and implementing the **interval halving algorithm**.
- Practicing the use of static methods in Java.

## Algorithm
The **interval halving algorithm** determines the root of a number by iteratively narrowing the range (`low` to `high`) until the correct root is found. This ensures that:
Where `#n` is the original value of `n`.

## Features
1. **Input**:
   - A `NaturalNumber` object (`n`) and an integer (`r`) representing the desired root.
   - Example: Find the 3rd root of `64`.

2. **Output**:
   - The input `n` is updated to its `r`-th root.
   - Example: `64` becomes `4` (since `4^3 = 64`).

3. **Constraints**:
   - `r >= 2`.

## Technologies Used
- Java
- Custom `NaturalNumber` class

## How to Run
1. Clone the repository:
   ```bash
   git clone [repository URL]
