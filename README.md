# greatest-of-3numbers
def grt3(a,b,c) :
if(a>b):
 if(a>c):
   return a
if(b>c):
 return b
 else:
  return c
a=int(input("enter a"))
b=int(input("enter b"))
c=int(input("enter c"))
d=grt3(a,b,c)
print(d)
