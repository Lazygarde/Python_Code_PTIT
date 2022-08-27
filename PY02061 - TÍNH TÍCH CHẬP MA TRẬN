# Lazygarde

t = int(input())
for z in range(t) :
    n, m = [int(x) for x in input().split()]
    a = [[0]] * n
    b = [[0]] * 3
    s = 0
    for i in range(n) : a[i] = [int(x) for x in input().split()]
    for i in range(3) : b[i] = [int(x) for x in input().split()]
    for i in range(2, n) :
        for j in range(2, m) :
            s += a[i - 2][j - 2] * b[0][0] 
            s += a[i - 2][j - 1] * b[0][1]
            s += a[i - 2][j] * b[0][2]
            s += a[i - 1][j - 2] * b[1][0]
            s += a[i - 1][j - 1] * b[1][1]
            s += a[i - 1][j] * b[1][2]
            s += a[i][j - 2] * b[2][0]
            s += a[i][j - 1] * b[2][1]
            s += a[i][j] * b[2][2]
    print(s)
