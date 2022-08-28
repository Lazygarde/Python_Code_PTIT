# Lazygarde

import math

def nto(n) :
    if n < 2 : return 0
    for i in range(2, int(math.sqrt(n)) + 1) :
        if n % i == 0 : return 0
    return 1

n = int(input())
a = [int(x) for x in input().split()]
b = {}
for i in a : b[i] = 1
a = list(b)
n = len(a)
ok = 0
for i in range(1, n) : a[i] += a[i - 1]
for i in range(n) :
    if nto(a[i]) and nto(a[n - 1] - a[i]) :
        ok = 1
        print(i)
        break
if ok == 0 : print("NOT FOUND")
