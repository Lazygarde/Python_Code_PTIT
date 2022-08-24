# Lazygarde

import math

class Fraction :
    def __init__(self, numerator, denominator):
        self.numerator = numerator
        self.denominator = denominator
    def compact(self) :
        k = math.gcd(self.numerator, self.denominator)
        self.numerator = int(self.numerator / k)
        self.denominator = int(self.denominator / k)
    def add(self, x) :
        a = self.denominator * x.numerator + x.denominator * self.numerator
        b = self.denominator * x.denominator
        self.numerator = a
        self.denominator = b
    def output(self) :
        print(self.numerator, "/", self.denominator, sep = "")

f = [int(x) for x in input().split()]
a = Fraction(f[0], f[1])
b = Fraction(f[2], f[3])
a.add(b)
a.compact()
a.output()
