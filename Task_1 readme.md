
# Python Program: Check if a Number is Even or Odd

This Python script allows the user to input a number and checks whether it is even or odd using the modulo operator `%`.

## How It Works

1. The user is prompted to input an integer.
2. The program checks if the number is divisible by 2 using `num % 2 == 0`.
3. If true, it prints "It is an even number", else it prints "It is an odd number".

## Python Code

```python
num = int(input("enter a number: "))
if (num % 2 == 0):
    print("It is an even number")
else:
    print("it is an odd number")
```

## Example

```
enter a number: 7
it is an odd number

enter a number: 10
It is an even number
```

## Requirements

- Python 3.x
