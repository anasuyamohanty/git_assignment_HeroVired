# Git and GitHub Assignment
This assignment has 2 python programs
 - CalculatorPlus python program
 - GeometryCalculator python program
 
Following document discusses about the two python programs in detailed with **screenshots**

## Program 1. CalculatorPlus Application

A simple Python calculator app that provides basic arithmetic operations and square root calculation.

### Features
- Addition: `add(a, b)`
- Subtraction: `subtract(a, b)`
- Multiplication: `multiply(a, b)`
- Division with safe handling of division-by-zero: `divide(a, b)`
- Square root calculation with input check: `square_root(x)`

### Repository Structure
git_assignment_HeroVired/
<br>├── CalculatorPlus.py    # Main calculator application
<br>├── README.md           # Project documentation
<br>└── .git/              # Git version control

### Running the application
```
python calculator.py
```

### Example Output
```
16 + 4 = 20
16 - 4 = 12
16 * 4 = 64
16 / 4 = 4.0
```

### Release Information
- **Version**: 1.0.0
- **Release Date**: October 15, 2025
- **Tag**: `v1.0.0`
- **Commit Hash**: `7cf6d1f `
- **Release Notes**: Initial release with basic arithmetic operations

### Screenshots of the execution of the program 

a & b. Add CalculatorPlus.py and execute it
<img width="940" height="796" alt="image" src="https://github.com/user-attachments/assets/d4d92366-41b9-4374-89d1-e1e1501523aa" />

c. Merge dev branch to main branch and create a release version 1 for Calculator Plus app
<img width="940" height="332" alt="image" src="https://github.com/user-attachments/assets/619801f5-8c12-44a4-9f81-ad95cbda6179" />

d. Added one of the classmate as a collaborator 

e & f. Create a new branch feature/sqrt and add the squre root function 
<img width="940" height="953" alt="image" src="https://github.com/user-attachments/assets/cecf46a9-303d-4f44-ac9e-3f939d04196a" />

g. Switch back to dev branch and fix the bug that cannot divide by ZERO
<img width="940" height="1018" alt="image" src="https://github.com/user-attachments/assets/1807c202-1cb1-47c3-9c7d-45db1d1b68c7" />

h & i. Raise Pull Request to merge the code from Dev branch to main branch and request a code review 
<img width="940" height="903" alt="image" src="https://github.com/user-attachments/assets/761a15af-a818-4aa7-b2cc-7591e8206cab" />

j. Merge feature/sqrt branch to dev<br>
Test Scenario - 1 : Normal execution
<img width="940" height="983" alt="image" src="https://github.com/user-attachments/assets/03009457-99e3-4419-a1da-f32230e2c73a" />

Test Scenario - 2 : A number divide by zero
<img width="940" height="962" alt="image" src="https://github.com/user-attachments/assets/5d266e32-40e7-49a5-91b5-5c0f220ee050" />

k. Merge the code from dev to main branch. Create a new release with version 2
<img width="940" height="491" alt="image" src="https://github.com/user-attachments/assets/be445c2d-9665-401c-9ba6-93a991f712e4" />
