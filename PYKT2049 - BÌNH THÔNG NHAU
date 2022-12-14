par = [0] * 10004
rankz = [0] * 10004

def init() :
    for i in range(10004) :
        par[i] = i
        rankz[i] = 1

def find(u) :
    if par[u] != u : par[u] = find(par[u])
    return par[u]

def join(u, v) :
    u = find(u)
    v = find(v)
    if u == v : return
    if rankz[u] == rankz[v] : rankz[u] += 1
    if rankz[u] < rankz[v] : par[u] = v
    else : par[v] = u

init()
q = int(input())
for i in range(q) :
    u, v, t = map(int, input().split())
    if t == 1 : join(u, v)

    else :
        u = find(u)
        v = find(v)
        if u == v : print("1")
        else : print("0")
