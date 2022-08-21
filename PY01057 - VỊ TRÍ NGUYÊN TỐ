# Lazygarde
import math
def nto(n) :
    if n < 2 : return 0
    for i in range(2, int(math.sqrt(n)) + 1) :
        if n % i == 0 : return 0
    return 1
def check(s) :
	for i in range(len(s)) :
		if nto(i) != nto(int(s[i])) : return 0
	return 1
t = int(input())
for i in range(t) :
	s = input()
	if check(s) == 1 : print("YES")
	else : print("NO")
