# Lazygarde

import math

def nto(n) :
    if n < 2 : return 0
    for i in range(2, int(math.sqrt(n)) + 1) :
        if n % i == 0 : return 0
    return 1

n, m = [int(x) for x in input().split()]
for z in range(n) :
    a = [int(x) for x in input().split()]
    for i in a :
        if nto(i) == 1 : print(1, end = " ")
        else : print(0, end = " ")
    print()
