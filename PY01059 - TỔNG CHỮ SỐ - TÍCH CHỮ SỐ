t = int(input())
for i in range(t) :
    s = input()
    s1 = 0
    s2 = 1
    ok = 0
    for i in range(len(s)) :
        if i % 2 == 0 : s1 += int(s[i])
        else :
            if s[i] != '0' :
                ok = 1
                s2 *= int(s[i])
    if ok == 0 : s2 = 0
    print(s1, s2)
