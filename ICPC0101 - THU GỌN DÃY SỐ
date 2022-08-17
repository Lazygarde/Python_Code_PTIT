n = int(input())
a = [int(x) for x in input().split()]
b = []
for i in a:
    if len(b) == 0:
        b = b + [i]
    else:
        if (b[-1] + i) % 2 == 0:
            b.pop()
        else:
            b = b + [i]
print(len(b))
