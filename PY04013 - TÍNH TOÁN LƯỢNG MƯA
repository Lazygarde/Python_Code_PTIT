# Lazygarde

def time(x, y):
    return y[0] * 60 + y[1] - x[0] * 60 - x[1]

a = {}
n = int(input())
for i in range(n) :
    ten = input()
    x = [int(i) for i in input().split(':')]
    y = [int(i) for i in input().split(':')]
    luongMua = int(input())
    if ten not in a:
        a[ten] = (time(x, y), luongMua)
    else:
        a[ten] = (a[ten][0] + time(x, y), a[ten][1] + luongMua)
    
p = 1
for i in a:
    print('T{:02d}'.format(p), i, "{:.2f}".format(a[i][1] * 60 / a[i][0]))
    p += 1
