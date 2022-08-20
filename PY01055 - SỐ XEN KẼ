def check(s) :
    if len(s) % 2 == 0 or s[0] == s[1] : return False
    for i in range(2, len(s), 2) :
        if s[i] != s[0] : return False
    return True
t = int(input())
for i in range(t) :
    s = input()
    if check(s) == True : print("YES")
    else : print("NO")
