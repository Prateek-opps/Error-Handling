Experiment-15

Name-Prateek Sinha

Class-ENTC(A3)

Prn-24070123077

# C++ Programs: Exception Handling

This repository contains two C++ programs that demonstrate **exception handling** using both custom and built-in exception mechanisms:
1. **Voting Eligibility Checker**
2. **Safe Division of Two Numbers**

These examples teach how to handle unexpected inputs or runtime errors gracefully using `try`, `catch`, and `throw`.

---

## 1️ Program: Voting Eligibility Checker
### Theory
This program uses a **user-defined exception class (`VotingException`)** to handle cases where a person is not eligible to vote.  
- **Concept:** If the user's age is below 18, the program throws a `VotingException` with a custom error message.  
- **Key Elements:**  
  - `throw` is used to raise the exception.  
  - `catch` block catches the object of the custom class.  
  - A member function (`showMessage`) displays the error.

---

## 2️ Program: Safe Division of Two Numbers
### Theory
This program performs division between two integers while checking for:
- **Negative Input:** If either number is negative, it throws an exception.
- **Division by Zero:** If the divisor is zero, it throws a different exception.

Instead of a custom class, it throws a **string literal (`const char*`)** and catches it in a generic `catch` block.

---

## Conclusion
These two programs demonstrate how **exceptions** can prevent a program from crashing and provide meaningful feedback to users:
- **Custom Exceptions:** The Voting program shows how to create and throw user-defined exceptions for specific scenarios.
- **Standard Exception Mechanism:** The Division program shows how to handle common runtime errors (like invalid input or division by zero) using simple `throw` and `catch` blocks.

By mastering these techniques, programmers can build applications that handle unexpected situations gracefully, ensuring safer and more reliable C++ programs.
