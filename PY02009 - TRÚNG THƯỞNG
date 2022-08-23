# Lazygarde

t = int(input())
for z in range(t) :
    n = int(input())
    m = {}
    for i in range(n) :
        x = int(input())
        if x in m : m[x] += 1
        else : m[x] = 1
    s = 0
    for i in m :
        if m[i] > s :
            s = m[i]
            p = i
        elif m[i] == s :
            p = min(p, i)
    print(p)
