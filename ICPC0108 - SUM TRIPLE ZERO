# Lazygarde

t = int(input())
for k in range(0,t):
	n = int(input())
	a = sorted([int(x) for x in input().split()])
	s = 0
	for i in range(0, n - 2) :
		l = i + 1
		r = len(a) - 1
		x = a[i]
		while l < r :
			if x + a[l] + a[r] == 0:
				s += 1
				l += 1
			elif x + a[l] + a[r] < 0 :
				l += 1
			else: 
				r -= 1
	print(s)
