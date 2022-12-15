def check(n, k, u, v, ke) :
    q, a = [u], [0] * (n + 1)
    a[u] = 1
    while len(q) > 0 :
        x = q.pop()
        if x == v : return False
        for i in ke[x] :
            if a[i] == 0 and i != k :
                q.append(i)
                a[i] = 1
    return True 

for t in range(int(input())) :
    n, m, u, v = [int(x) for x in input().split()]
    ke = []
    for i in range(n + 1) : ke.append([])
    for i in range(m) :
        x, y = [int(x) for x in input().split()]
        ke[x].append(y)
    ans = 0
    for i in range(1, n + 1) :
        if i != u and i != v :
            if check(n, i, u, v, ke) : ans += 1
    print(ans)
