# Lazygarde

x = input()
n = len(x)
a = [0] * n

def Try(s, k) :
    if k == n :
        print(s)
        return
    for i in range(n) :
        if a[i] == 0 :
            a[i] = 1
            Try(s + x[i], k + 1)
            a[i] = 0
            
Try("", 0)
