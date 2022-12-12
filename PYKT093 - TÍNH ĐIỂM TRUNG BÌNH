from math import ceil

class SV:
    def __init__(self, ma, ten, d):
        self.ma = 'SV{:02d}'.format(ma)
        self.ten = self.rename(ten)
        self.d = d

    def rename(self, ten) -> str:
        return ' '.join(i.title() for i in ten.strip().split())
    
    def __str__(self) -> str:
        return '{:s} {:s} {:.2f} {:d}'.format(self.ma, self.ten, ceil(self.d * 100) / 100, self.rank)

a = []
for i in range(int(input())):
    a.append(SV(i + 1, input(), (3 * int(input()) + 3 * int(input()) + 2 * int(input())) / 8))
a = sorted(a, key = lambda x: (-x.d, x.ma))
a[0].rank = 1
for i in range(1, len(a)):
    a[i].rank = a[i-1].rank if a[i].d == a[i-1].d else i + 1
print(*a, sep = '\n')
