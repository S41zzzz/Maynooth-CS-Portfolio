# Compound Interest Calculator in Java

A simple, lightweight Java command-line application designed to calculate compound interest and future investment values based on user inputs.

## Features
- **Interactive User Prompts:** Collects the principal amount, annual interest rate (as a decimal), and investment duration in years via standard input (`Scanner`).
- **Compound Interest Calculation:** Computes the future value of an investment using the standard compound interest formula.
- **Interest Breakdown:** Calculates and displays the total interest earned separately from the final principal balance.

---

## Formula Used
The application uses the standard compound interest formula:

$$\text{Future Value} = P \times (1 + r)^t$$

$$\text{Total Interest} = \text{Future Value} - P$$

Where:
- **$P$** = Principal amount (initial investment)
- **$r$** = Annual interest rate (expressed as a decimal, e.g., $5\% = 0.05$)
- **$t$** = Number of years

---

## Getting Started

### Prerequisites
- **Java Development Kit (JDK):** Version 8 or higher installed on your machine.

### Compilation and Execution
1. Save the code into a file named `compoundInterestCalculator.java`.
2. Open your terminal or command prompt and navigate to the directory containing the file.
3. Compile the Java program:
   ```bash
   javac compoundInterestCalculator.java
