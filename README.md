# Palindrome-Number-cheak

n=int(input("Enter the number"))

temp=n

s=0

while n!=0:

d=n%10  
  
   #Example=121
   
   s=s*10+d
   
   n=n//10

if temp==s:

   print("The Palidrome number")

else:

  print("The Not a Palindrome number ")
