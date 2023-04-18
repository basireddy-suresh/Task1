# Task1
Write  a 5 programs 
print("Hy")
# add two numbers
number1 = input("First number: ")
number2 = input("\nSecond number: ")
sum = float(number1) + float(number2)
print("The sum of {0} and {1} is {2}" .format(number1, number2, sum))

# maximum of two numbers
def maximum(a, b):
	if a >= b:
		return a
	else:
		return b
a = 2
b = 4
print(maximum(a, b))

# factorial of given number
def factorial(n):

	return 1 if (n==1 or n==0) else n * factorial(n - 1)

num = 5
print("Factorial of",num,"is",factorial(num))

#prime numbers
num = 11
if num > 1:
	for i in range(2, int(num/2)+1):
		if (num % i) == 0:
			print(num, "is not a prime number")
			break
	else:
		print(num, "is a prime number")
else:
	print(num, "is not a prime number")

