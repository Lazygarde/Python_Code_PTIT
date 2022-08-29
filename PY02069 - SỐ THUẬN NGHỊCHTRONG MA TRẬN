# Lazygarde

def tn(s) :
    if len(s) > 1 and s == s[::-1] : return 1
    return 0

n, m = [int(x) for x in input().split()]
a = [[0]] * n
x = 0
for i in range(n) : a[i] = input().split()
for i in range(n) :
    for j in range(m) :
        if tn(a[i][j]) and int(a[i][j]) > int(x) : x = a[i][j]
if x == 0 : print('NOT FOUND')
else : print(x)
for i in range(n) :
    for j in range(m) :
        if a[i][j] == x : print('Vi tri [', i, '][', j, ']', sep = '')
