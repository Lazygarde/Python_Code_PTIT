# Lazygarde

import math

def nto(n) :
    if n < 2 : return False
    for i in range(2, int(math.sqrt(n)) + 1) :
        if n % i == 0 : return False
    return True 

n = int(input())
a = [int(x) for x in input().split()]
b, c, d = [], [], [0] * n
for i in range(n) :
    if nto(a[i]) == 0 : b.append(a[i])
    else :
        c.append(a[i])
        d[i] = 1
c = sorted(c)
p1, p2 = 0, 0
for i in range(n) :
    if d[i] == 1:
        print(c[p2], end = ' ')
        p2 += 1
    else :
        print(b[p1], end = ' ')
        p1 += 1
