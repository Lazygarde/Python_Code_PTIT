import math
def nto(n) :
    if n < 2 : return False
    for i in range(2, int(math.sqrt(n)) + 1) :
        if n % i == 0 : return False
    return True
def check(s) :
    x = 0
    for i in range(len(s)) :
        if (i % 2) != (int(s[i]) % 2) : return False
        x += int(s[i])
    if nto(x) == True : return True
    else : return False
t = int(input())
for i in range(t) :
    s = input()
    if check(s) == True : print("YES")
    else : print("NO")
