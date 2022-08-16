import math
t = int(input())
for i in range(t) : 
  n = int(input())
  print("1", end = "")
  for i in range(2, int(math.sqrt(n)) + 1) :
    s = 0
    while n % i == 0 :
      s += 1
      n /= i
    if s != 0 :
      print(" * ", end = "")
      print(i, end = "^")
      print(s, end = "")
  if n > 1 :
    print(" * ", end = "")
    print(int(n), end = "^1")
  print()
