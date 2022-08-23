# Lazygarde

import functools

def cnt(n) :
    s = 0
    while n != 0 :
        s += n % 10
        n = int(n / 10)
    return s

def cmp(a, b) :
    if cnt(a) == cnt(b) :
        if a > b : return 1
        else : return -1
    elif cnt(a) > cnt(b) : return 1
    else : return -1
    
t = int(input())
for i in range(t) :
    n = int(input())
    a = [int(x) for x in input().split()]
    a = sorted(a, key = functools.cmp_to_key(cmp))
    for i in a : print(i, end = " ")
    print()
