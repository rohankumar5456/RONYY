# RONYY
n=int(input("enter the number :"))
r=0
s=0

while(n>0):
 r=n%10
 s=s+r
 n=n=n/10
print("sum of digits :",int(s))
