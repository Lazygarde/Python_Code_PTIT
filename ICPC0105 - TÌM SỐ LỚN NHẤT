t = int(input())
for i in range(t) :
    n = input()
    n = n + 'z'
    ans = 0
    s = 0
    for i in range(len(n)) :
        if n[i].isalpha() :
            if i != 0 and n[i - 1].isdigit() : ans = max(ans, s)
            s = 0
        else : s = s * 10 + int(n[i])
    print(ans)
