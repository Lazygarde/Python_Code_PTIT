# Lazygarde

t = int(input())
for z in range(t) :
    n = int(input())
    a = [int(x) for x in input().split()]
    st = []
    for i in range(n) :
        while len(st) > 0 and a[st[-1]] <= a[i] : st.pop()
        if len(st) == 0 : print(i + 1, end = " ")
        else : print(i - st[-1], end = " ")
        st.append(i)
    print()
