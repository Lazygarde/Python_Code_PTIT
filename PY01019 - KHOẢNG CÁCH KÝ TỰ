def check(s) :
    x = ""
    for i in s : x = i + x
    for i in range(1, len(s)) :
        if abs(ord(s[i]) - ord(s[i - 1])) != abs(ord(x[i]) - ord(x[i - 1])) : return False
    return True
t = int(input())
for i in range(t) :
    s = input()
    if check(s) == True : print("YES")
    else : print("NO")
