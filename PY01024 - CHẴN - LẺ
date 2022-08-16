def check(s) :
  n = int(s)
  m = 0
  while n > 0 :
    m += n % 10
    n = int(n / 10)
  if m % 10 != 0 : return False
  for i in range(1, len(s)) :
    if abs(int(s[i]) - int(s[i - 1])) != 2 : return False
  return True
t = int(input())
for i in range(t) :
  s = input()
  if check(s) == True : print("YES")
  else : print("NO")
