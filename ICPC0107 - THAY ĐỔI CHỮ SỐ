t = int(input())
for i in range(t) : 
    m, n = [x for x in input().split()]
    a = input().strip()
    if(a.count(' ')) : a, b = a.split()
    else : b = input()
    p = min(m, n)
    q = max(m, n)
    print(int(a.replace(q, p)) + int(b.replace(q, p)), end=" ")
    print(int(a.replace(p, q)) + int(b.replace(p, q)))
