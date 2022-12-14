class SV :
    def __init__(self, ma, ten, team, tr) :
        self.ma = 'C{:03d}'.format(ma)
        self.ten = ten
        self.team = team
        self.tr = tr
        
n = int(input())
t = [1]
for i in range(n) :
    t.append([input(), input()])
n = int(input())
a = []
for i in range(n) :
    ten = input()
    team = input()
    a.append(SV(i + 1, ten, t[int(team[4::])][0], t[int(team[4::])][1]))
a = sorted(a, key = lambda x : x.ten)
for i in a :
    print(i.ma, i.ten, i.team, i.tr)
