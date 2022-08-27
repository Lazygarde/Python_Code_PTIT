# Lazygarde

a = [0] * 1000001

def era() :
    a[0] = a[1] = 1
    for i in range(2, 1000) :
        if a[i] == 0 :
            for j in range(i * i, 1000001, i) : a[j] = 1

era()
t = int(input())
for i in range(t) :
    n = int(input())
    s = 0
    for i in range(6, n) :
        if a[i] == 0 and a[i - 6] == 0 and (a[i - 2] == 0 or a[i - 4] == 0) : s += 1
    print(s)
