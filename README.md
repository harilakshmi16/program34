print("enter the number:")
num=int(input())
rev=0
temp=num
while temp>0:
rem=temp%10
rev=rem+(rev*10)
temp=int(temp/10)
if rev==num:
print("\n It is a palindrom number")
else:
print("\n It is not a palindrom number")
Output:
enter the number:
12
It is not a palindrom number
