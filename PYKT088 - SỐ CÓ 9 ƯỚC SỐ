# Lazygarde

n, s, i = int(input()), 0, 2
l = int(n ** (0.5))
a = [i for i in range(l + 1)]
while i * i <= l :
    if a[i] == i :
        for j in range(i * i, l + 1, i): 
            if a[j] == j : a[j] = i
    i += 1
for i in range(2, l + 1) : 
    p = a[i]
    q = a[i // a[i]]
    if p * q == i and q != 1 and p != q : s += 1
    elif a[i] == i :
        if i ** 8 <= n : s += 1
print(s)
