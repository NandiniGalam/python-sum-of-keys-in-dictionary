# python-sum-of-keys-in-dictionary
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
res=0 
for i in d:
  res=res+i
print(res)  
