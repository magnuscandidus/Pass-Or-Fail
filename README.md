# Pass-Or-Fail
# cook your dish here
t=int(input())
for i in range(t):
  n,x,p=map(int,input().split())
  if (x*3)+((n-x)*-1)>=p: 
    print("pass")
  else:
      print("fail")
