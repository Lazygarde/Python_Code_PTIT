# Lazygarde

n = int(input())
a = [float(x) for x in input().split()]
Max = max(a)
Min = min(a)
s = 0
cntMax = 0
cntMin = 0
for i in a :
    s += i
    if i == Max : cntMax += 1
    if i == Min : cntMin += 1
print("{:.2f}".format((s - cntMax * Max - cntMin * Min) / (n - cntMax -cntMin)))
