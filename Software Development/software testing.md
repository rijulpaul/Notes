# Software Testing
## Fundamentals
### What is Software Testing?
Testing is the process of evaluating a software application to find any gaps, errors, or missing requirements contrary to the actual requirements.
### The 7 core principles of testing
- Testing shows the presence of defects, not their absence.
- Exhaustive testing is impossible.
- Early testing saves time and money.
- Defects cluster together (Pareto Principle).
- Beware of the pesticide paradox (repeating the same tests won't find new bugs).
- Testing is context-dependent.
- Absence-of-errors fallacy (a bug-free but useless system is still a failure).
## Levels of Testing
### Testing Pyramid
You should have many small, fast `Unit Tests` at the base, fewer `Integration Tests` in the middle, and even fewer large, slow `End-to-End (System/UI) Tests` at the top.
### Functional vs Non-Functional Testing
#### Functional Testing 
Checks if the software does the right thing. (e.g., Does the "Login" button log the user in?). Key types:
- **Smoke Testing**: A quick check to see if the main features are working. "Is the application stable enough to test?"
- **Regression Testing**: Re-running old tests to make sure new changes haven't broken existing features. This is the #1 candidate for automation!
- **UI Testing**
- **API Testing**
#### Non-Functional Testing
Checks how well the software performs a function. (e.g., How fast does the login happen? Can 1000 users log in at once?). Key types:
- **Performance Testing**: Checks speed, responsiveness, and stability under load.
- **Usability Testing**: Checks if the application is user-friendly and intuitive.
- **Security Testing**
- **Compatibility Testing**
- **Reliability Testing**
## Types of Testing
### Black-Box Testing
You don't need to see the code. You only focus on inputs and outputs.
- **Equivalence Partitioning**: Divide input data into valid and invalid groups. Test one value from each group.
- **Boundary Value Analysis**: An extension of EP. Test the values at the edges of the partitions.
- Decision Table Testing
- State Transition Testing
### White-Box Testing
- Statement Coverage
- Branch Coverage
- Path Coverage
### Experience-Based Testing
- Exploratory Testing
- Error Guessing
