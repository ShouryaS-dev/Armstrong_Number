# Armstrong Number Checker

A simple C++ program that checks whether a given number is an **Armstrong number**.

## Description

The program takes an integer as input and calculates the number of digits in it. It then extracts each digit and raises it to the power of the total number of digits.

The calculated sum is compared with the original number:

* If both are equal → the number is an **Armstrong number**.
* Otherwise → it is **not an Armstrong number**.

### Example

For `153`:

```text
1³ + 5³ + 3³
= 1 + 125 + 27
= 153
```

Therefore, `153` is an Armstrong number.

## Concepts Used

* `while` loops
* Functions
* Integer division
* Modulus operator `%`
* `std::pow()`
* User input/output
* Basic number manipulation

## Example Output

```text
Enter a number : 153
The given number 153 is an armstrong number
```

## Author

Created as part of my C++ learning journey.
