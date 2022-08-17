import math
f = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9', 'A', 'B', 'C', 'D', 'E', 'F']
t = int(input())
for i in range(t) : 
    n = int(input())
    a = input()
    n = int(math.log(n)/math.log(2))
    while len(a) % n != 0 : a = '0' + a
    for i in range(0, len(a), n) :
        s = 0
        for j in range(i, i + n):
            if a[j] == '1' : s += pow(2, n - j + i - 1)
        print(f[s],end = "")
    print()
