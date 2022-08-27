# Lazygarde

class Rectangle :
    def __init__(self, w, h, color) :
        self.w = w
        self.h = h
        self.color = color[0:1:].upper() + color[1::].lower()

    def check(self) :
        if self.w <= 0 or self.h <=0 : return 0
        return 1
    
    def output(self) :
        if self.check() == 1 : print((self.w + self.h) * 2, self.w * self.h, self.color, sep = ' ')
        else : print('INVALID')

a = input().split()
rec = Rectangle(int(a[0]), int(a[1]), (a[2]))
rec.output()
