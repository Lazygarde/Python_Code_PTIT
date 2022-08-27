# Lazygarde

f = '0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ'
t = int(input())
for i in range(t):
    n, k = [int(x) for x in input().split()]
    s = ''
    while (n > 0):
        x = n % k
        s = f[x] + s
        n = int(n / k)
    print(s)
