import math
def nto(n) :
    if n < 2 : return False
    for i in range(2, int(math.sqrt(n)) + 1) :
        if n % i == 0 : return False
    return True
def check(n) :
    s = 0
    for i in n :
        s += int(i)
    if nto(s) : return True
    return False
t = int(input())
for i in range(t) :
    n = input()
    if check(n) == True : print("YES")
    else : print("NO")
