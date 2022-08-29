# Lazygarde

a = input()
n = int(input())
b = {}
for i in range(int(len(a) / 2)) :
    k = int(a[0]) * 10 + int(a[1])
    if k in b : b[k] += 1
    else : b[k] = 1
    a = a[2::]
ok = 0
for i in sorted(b) :
    if b[i] >= n :
        ok = 1
        print(i, b[i])
if ok == 0 : print("NOT FOUND")
