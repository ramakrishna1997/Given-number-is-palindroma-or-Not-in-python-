# Given-number-is-palindroma-or-Not-in-python-
number=int(input("Enter the number"))
temp=number
reverse = 0
while(number>0):
    digit=number%10
    reverse=reverse*10+digit
    number=number//10
if(temp==reverse):
    print("Yes,it is Palidroma number")
else:
    print("It is Not a palidroma number")
