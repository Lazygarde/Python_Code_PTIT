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
    for i in range(1, n) :
        k = int(str(i)[::-1])
        if k > i and k < n and a[i] == 0 and a[k] == 0 :
            print(i, k, end = ' ')
    print()
