# SafeLog Password Validator

## About the Project

This project is a simple Java-based password validation tool built for a cybersecurity use case.
The goal is to ensure that users create strong passwords by enforcing a few basic security rules and giving clear feedback when those rules are not met.

Instead of just saying “invalid password,” the program explains *what exactly is missing*, making it more user-friendly and practical.

---

## What It Does

The program checks whether a password:

* Has at least 8 characters
* Contains at least one uppercase letter
* Contains at least one digit (0–9)

If any condition fails, it tells the user exactly why.
It keeps asking for a new password until a valid one is entered.


## Example

```
Enter password: hello
Too short (minimum 8 characters required)

Enter password: helloworld
Missing an uppercase letter
Missing a digit

Enter password: Hello123
Strong password accepted!
```
