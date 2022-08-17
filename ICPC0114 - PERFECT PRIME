import math
def nto(n) :
    if n < 2 : return False
    for i in range(2, int(math.sqrt(n)) + 1) :
        if n % i == 0 : return False
    return True
def check(n) :
    m = 0
    s = 0
    x = n
    while n != 0 :
        k = n % 10
        if nto(k) == False : return False
        m = m * 10 + k
        s += k
        n = int(n / 10)
    if nto(s) and nto(x) and nto(m) : return True
    return False
t = int(input())
for i in range(t) :
    n = int(input())
    if check(n) == True : print("Yes")
    else : print("No")
