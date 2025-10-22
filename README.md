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

### Installation
Clone the repository:
```bash
git clone https://github.com/anasuyamohanty/git_assignment_HeroVired
cd git_assignment_HeroVired
```
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
- **Tag**: `v1.0`
- **Commit Hash**: `e91499e `
- **Release Notes**: Calculator plus app has basic arithmetic operations

### Screenshots of the execution of the program 

a & b. Add CalculatorPlus.py and execute it
<img width="940" height="796" alt="image" src="https://github.com/user-attachments/assets/d4d92366-41b9-4374-89d1-e1e1501523aa" />

c. Merge dev branch to main branch and create a release version 1 for Calculator Plus app
<img width="892" height="340" alt="image" src="https://github.com/user-attachments/assets/67dba26a-4359-4fda-b220-c21682aa3bcb" />


d. Added one of the classmate as a collaborator 
<img width="880" height="419" alt="image" src="https://github.com/user-attachments/assets/38fe4dbb-d09f-451d-b7e3-b7976439e766" />


e & f. Create a new branch feature/sqrt and add the squre root function 
<img width="940" height="953" alt="image" src="https://github.com/user-attachments/assets/cecf46a9-303d-4f44-ac9e-3f939d04196a" />

g. Switch back to dev branch and fix the bug that cannot divide by ZERO
<img width="940" height="1018" alt="image" src="https://github.com/user-attachments/assets/1807c202-1cb1-47c3-9c7d-45db1d1b68c7" />

h. After completing the feature implementation and ensuring that the application works correctly, create a pull request targeting the main branch. 
Test Scenario - 1 : Normal execution
<img width="940" height="983" alt="image" src="https://github.com/user-attachments/assets/03009457-99e3-4419-a1da-f32230e2c73a" />

Test Scenario - 2 : A number divide by zero
<img width="940" height="962" alt="image" src="https://github.com/user-attachments/assets/5d266e32-40e7-49a5-91b5-5c0f220ee050" />

i & j. Request a code review from a team member and make any necessary improvements based on the review feedback. 
Once the code reviewer approves your pull request, merge the "feature/sqrt" branch into the ‘dev’ branch.
<img width="770" height="305" alt="image" src="https://github.com/user-attachments/assets/7ac5f05f-af81-4ef8-96f0-de5241f9c879" />
<img width="831" height="230" alt="image" src="https://github.com/user-attachments/assets/e3b0c046-b698-4fe7-97e3-7a7359c57e18" />



k. Merge the code from dev to main branch. Create a new release with version 2
<img width="858" height="359" alt="image" src="https://github.com/user-attachments/assets/3575cb02-f7f9-4cd4-bcfd-d0c990a5c6fe" />
<img width="786" height="398" alt="image" src="https://github.com/user-attachments/assets/387284f9-5729-4396-b0b5-5574acc3ee24" />

> [!NOTE]  
> End of CalculatorPlus Python Program

## Program 3. GeormetryCalculator Pythong Program

A simple Python app that provides basic area calculator for Rectangle and Circle.

### Features
- Calculate Circle Area
- Calculate Rectangle Area

### Repository Structure
git_assignment_HeroVired/
<br>├── GeometryCalculator.py    # Main application
<br>├── README.md                # Project documentation
<br>└── .git/                    # Git version control

### Installation
Clone the repository:
```bash
git clone https://github.com/anasuyamohanty/git_assignment_HeroVired
cd git_assignment_HeroVired
```

### Running the application
```
python GeometryCalculator.py
```

### Example Output
```
The area of the circle with radius 5 = 78.53981633974483
The area of the rectangle with length 10 and width 6 = 60
```

### Branching & Release Strategy (used in this assignment)
- `main` — production-ready code and releases.
- `dev` — integration/testing branch where features are merged before release.
- `feature/circle-area` — short-lived branches for feature development
- `feature/rectangle-area` — short-lived branches for feature development

### Screenshots of the execution of the program

a. Create a new branch **feature/circle-area**
<img width="940" height="174" alt="image" src="https://github.com/user-attachments/assets/c0118604-fa29-4c5a-b082-7df8ac53fb0e" />

b. Stash changes in feature/circle-area
<img width="745" height="606" alt="image" src="https://github.com/user-attachments/assets/b9543964-485c-472d-8956-e8ce29013ce1" /><br>
After stashing the feature, the code has saved but not committed
<img width="940" height="979" alt="image" src="https://github.com/user-attachments/assets/231bc959-bd4d-440b-9de6-08e8b450d115" />

c. Create a new branch **feature/rectangle-area**
<img width="940" height="654" alt="image" src="https://github.com/user-attachments/assets/c388efc6-469b-4fdf-b70b-7fd7966b552e" />

d. Stash changes in feature/rectangle-area
<img width="940" height="786" alt="image" src="https://github.com/user-attachments/assets/2ff93e2a-e967-42fc-a5ad-a6fd3266871f" />
After stashing the featre, the code has saved but not committed
<img width="940" height="967" alt="image" src="https://github.com/user-attachments/assets/388041f3-e3bc-4a19-87e3-416dca3bb33e" />

e. Switch back to feature/circle-area
<img width="940" height="985" alt="image" src="https://github.com/user-attachments/assets/6d44c640-4307-48e7-82c9-2fe1c328653d" />
After stash apply on feature/circle-area
<img width="940" height="1044" alt="image" src="https://github.com/user-attachments/assets/648a3f44-07ff-473a-ab6f-6ae51dbbc1d3" />

f. Commit and push feature/circle-area branch
<img width="940" height="1044" alt="image" src="https://github.com/user-attachments/assets/12fd4c2e-cdff-47c3-b820-1f03bc639919" />


g. Switch back to feature/rectangle-area
<img width="940" height="750" alt="image" src="https://github.com/user-attachments/assets/40c911f9-152c-47cb-8cbc-0bf430c5698a" />
After stash changes applied on feature/rectangle-area
<img width="940" height="953" alt="image" src="https://github.com/user-attachments/assets/ffb52f09-d7ec-4a93-9664-55fd2fcae945" />

h. Commmit and push feature/rectangle-area
<img width="940" height="953" alt="image" src="https://github.com/user-attachments/assets/5ba588d3-fd7d-4a9a-8801-42a286a4ffdb" />

i. Create two Pull Requests to merge both feature/circle-area and feature/rectangle-area branches to dev branch<br>

 1. Raised Pull Request and code review the feature/circle-area branch to dev branch
<img width="590" height="374" alt="image" src="https://github.com/user-attachments/assets/40aeb4e7-d483-4568-8c9c-55519c92869e" />


 2. Pull Request to merge the code from feature/rectangle-area to dev branch
<img width="623" height="391" alt="image" src="https://github.com/user-attachments/assets/347833f1-90b6-4992-9969-d15b917775fc" />


j. Create Pull Request to merge from dev branch to main branch and review the code
<img width="724" height="353" alt="image" src="https://github.com/user-attachments/assets/f4d08f47-2477-4a75-bc76-3c6e9f028b51" />


> [!NOTE]  
> End of GeoetryCalculator Python Program
