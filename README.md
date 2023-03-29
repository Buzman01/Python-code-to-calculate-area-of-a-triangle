# Python-code-to-calculate-area-of-a-triangle
# Read input values

a = float(input('Enter Value 1: '))
b = float(input('Enter value 2: '))
c = float(input('Enter value 3: '))

# calculate the semi-perimeter
s = (a + b + c) / 2

# calculate the area of trainagle
area = (s*(s-a)*(s-b)*(s-c)) ** 0.5
print('The area of the triangle is %0.2f' %area)
