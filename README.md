# factorial-with-and-without-list
#without list
a,b=map(int,input().split())
s=0
for i in range(a,b+1):
  r=1
  for j in range(1,i+1):
    r=r*j
  s=s+r
print(s)
#with list
a,b=map(int,input().split())
s=[]
for i in range(a,b+1):
  r=1
  for j in range(1,i+1):
    r=r*j
  s.append(r)
print(sum(s))
