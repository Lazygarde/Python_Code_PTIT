# Lazygarde

import math

b = [0] * 10001 

def era() :
    b[0] = b[1] = 1
    for i in range(2, int(math.sqrt(10000)) + 1) :
        if b[i] == 0 :
            for j in range(i * i, 10001, i) :
                b[j] = 1

era()
a = [0]
for i in range(10001) :
    if b[i] == 0 : a = a + [i]
    
n, k = [int(x) for x in input().split()]
p = 0
for i in range(n + 1) :
    k += a[p]
    print(k, end = " ")
    p += 1
