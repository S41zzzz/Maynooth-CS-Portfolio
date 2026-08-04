# Weight Converter in Java

A simple command-line Java application that converts weights between Kilograms (kg) and Pounds (lbs) based on user selection.

---

## Features
- **Interactive Menu:** Prompts the user to choose between two conversion directions:
  1. Kilograms to Pounds
  2. Pounds to Kilograms
- **Precise Calculations:** Uses the standard conversion factor ($1\text{ kg} \approx 2.20462\text{ lbs}$).
- **Formatted Output:** Handles user input validation and formats the results cleanly.

---

## Conversion Formulas Used
- **Kilograms to Pounds:** 
  $$\text{Pounds} = \text{Kilograms} \times 2.20462$$
- **Pounds to Kilograms:** 
  $$\text{Kilograms} = \frac{\text{Pounds}}{2.20462}$$

---

## Getting Started

### Prerequisites
- **Java Development Kit (JDK):** Version 8 or higher installed on your machine.

### Compilation and Execution
1. Save the code into a file named `Main.java`.
2. Open your terminal or command prompt and navigate to the folder containing the file.
3. Compile the Java program:
   ```bash
   javac Main.java
