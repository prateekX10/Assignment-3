# Assignment-3
# ASSIGNMENT - 1
# TASK - !
import math

def factorial(n):
  if n < 2:
    return 1
  else:
    return n * factorial(n-1)


n = int(input("Enter a number: "))
print("Factorial of", n, "is", factorial(n))

# TASK - 2
num = int(input("Enter a number: "))
print(math.sqrt(num))
print(math.log(num))
print(math.sin(num/2))
