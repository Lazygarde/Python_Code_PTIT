# Lazygarde

n = int(input())
a = [[]] * n
for i in range(n) :
    a[i] = [int(x) for x in input().split()]
p = int(input())
s1 = 0
s2 = 0
for i in range(n) :
    for j in range(n) :
        if i + j + 1 < n : s1 += a[i][j]
        elif i + j + 1 > n : s2 += a[i][j]
s = abs(s1 - s2)
if s <= p : print("YES")
else : print("NO")
print(s)
