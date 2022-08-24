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
    def output(self) :
        print(self.numerator, "/", self.denominator, sep = "")

a, b = [int(x) for x in input().split()]
f = Fraction(a, b)
f.compact()
f.output()
