t = int(input())
for z in range(t) :
    n = int(input())
    m = {}
    s = 0
    a = input().split()
    for i in a :
        if i in m :
            m[i] += 1
        else : m[i] = 1
    for i in a :
        if s < m[i] :
            s = m[i]
            p = i
    if s > n / 2 : print(p)
    else : print("NO")
