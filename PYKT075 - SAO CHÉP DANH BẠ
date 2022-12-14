class DT :
    def __init__(self, ten, sdt, ngay) :
        self.ten = ten
        self.sdt = sdt
        self.ngay = ngay
        self.x = ten.split()[-1]
    def getstr(self) :
        return self.ten + ': ' + self.sdt + ' ' + self.ngay
ip = open('SOTAY.txt', 'r')
inp = ip.read().split('\n')
a = []
while len(inp) > 0 :
    x = inp[0]
    inp.pop(0)
    if x[:4:] == 'Ngay' : ngay = x[5::]
    elif len(inp) > 0 :
        sdt = inp[0]
        inp.pop(0)
        a.append(DT(x, sdt, ngay))
a = sorted(a, key = lambda x : (x.x, x.ten))
ip.close()
ot = open('DIENTHOAI.txt', 'w')
for i in a : ot.write(i.getstr() + '\n')
ot.close()
