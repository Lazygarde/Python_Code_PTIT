# Lazygarde

def check(s) :
    if s[0] != '6' : return 0
    for i in range(len(s)) :
        if s[i] != '6' and s[i] != '8' : return 0
        if i >= 2 and s[i - 2:i + 1:] == '888' : return 0
    return 1

s = input()
if check(s) == 1 : print("YES")
else : print("NO")
