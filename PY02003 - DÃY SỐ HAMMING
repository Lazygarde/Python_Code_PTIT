# Lazygarde

m = {1 : 1}
while True :
    ok = 0
    a = []
    for i in m :
        if i < 10**18 :
            if not((i * 2) in m) :
                a.append(i * 2)
            if not((i * 3) in m) :
                a.append(i * 3)
            if not((i * 5) in m) :
                a.append(i * 5)
    for i in a :
        ok = 1
        m[i] = 1
    if ok == 0 : break
p = 1
a = sorted(list(m))
for i in a :
    m[i] = p
    p += 1
t = int(input())
for i in range(t) :
    n = int(input())
    if n in m : print(m[n])
    else : print("Not in sequence")
