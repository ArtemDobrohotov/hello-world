# hello-world
Ябатька
from math import ceil
epsilon = 5 * 10**-7
n = int(input())
x = float(input())
sum_ = float(input()) * x
i = n
while i > 0:
    a = float(input())
    sum_ += sum_ * x + a
    i -= 1
print(sum_)
