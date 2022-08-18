t = int(input())
for i in range(t) :
    s = input()
    n = len(s)
    k = 1
    for i in range(1, n) :
        if s[i] != s[i - 1] :
            print(k,end = "")
            print(s[i - 1], end = "")
            k = 1
        else : k += 1
    print(k, end = "")
    print(s[n - 1])
