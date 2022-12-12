class Mon :
    def __init__(self, maca, mamon, ten, ngaythi, giothi, nhom) :
        self.maca = 'T{:03d}'.format(maca)
        self.mamon = mamon
        self.ten = ten
        self.ngaythi = ngaythi
        self.ngay = int(ngaythi[:2:])
        self.thang = int(ngaythi[3:5:])
        self.nam = int(ngaythi[6::])
        self.giothi = giothi
        self.gio = int(giothi[:2:])
        self.phut = int(giothi[3::])
        self.nhom = nhom
        
m = {}
n, k = [int(x) for x in input().split()]
for i in range(n) :
    ma = input()
    mon = input()
    m[ma] = mon
a = []
for i in range(k) :
    ma, ngay, gio, nhom = input().split()
    a.append(Mon(i + 1, ma, m[ma], ngay, gio, nhom))
a = sorted(a, key = lambda x : (x.nam, x.thang, x.ngay, x.gio, x.phut, x.mamon))
for i in a :
    print(i.maca, i.mamon, i.ten, i.ngaythi, i.giothi, i.nhom)
