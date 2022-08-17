def giaithua(n) : 
    s = 1
    for i in range(n) : 
        s *= i + 1
    return s
def check(n) :
    s = 0
    m = n
    while n > 0 :
        s += giaithua(n % 10)
        n = int(n / 10)
    if s == m : return True
    else : return False
t = int(input())
for i in range(t) :
    n = int(input())
    if check(n) : print("Yes")
    else : print("No")
