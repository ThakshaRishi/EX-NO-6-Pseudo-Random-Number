# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:

```
import random
def main():
    count = int(input("Enter the number of random numbers to generate: "))
    min_val = int(input("Enter the minimum value: "))
    max_val = int(input("Enter the maximum value: "))
    print("\nPseudorandom numbers:")
    for _ in range(count):
        print(random.randint(min_val, max_val), end=' ')
    print()
if __name__ == "__main__":
    main()
```

# OUTPUT:

<img width="567" height="299" alt="image" src="https://github.com/user-attachments/assets/380cfeb1-705d-4ffe-be21-f36cbbf19402" />


# RESULT:
Thus, the Pseudorandom Number Generator using Standard Library has been implemented successfully.
