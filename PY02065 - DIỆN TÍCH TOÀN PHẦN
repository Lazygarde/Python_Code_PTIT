# Lazygarde

t = int(input())
for i in range(t):
    n, m = [int(x) for x in input().split()]
    a = [[0] * (m + 2)] * (n + 2)
    s = 2 * n * m
    for i in range(1, n + 1) :
        a[i] = [0] + [int(x) for x in input().split()] + [0]
    for i in range(1, n + 1) :
        for j in range(1, m + 1) :
            if a[i][j] == 0 : s -= 2
            if a[i][j] > a[i - 1][j] : s += a[i][j] - a[i - 1][j]
            if a[i][j] > a[i + 1][j] : s += a[i][j] - a[i + 1][j]
            if a[i][j] > a[i][j - 1] : s += a[i][j] - a[i][j - 1]
            if a[i][j] > a[i][j + 1] : s += a[i][j] - a[i][j + 1]
    print(s)
