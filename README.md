# Nitin-kumar-
my first program mini calculator 

first = int(input("Enter first number :"))
operator = input(" operator : =  " "+,-,/,%,*,**,")
second = int(input("Enter second number : "))

if  operator == "+":
    print( first + second  )

elif  operator == "-":
    print( first - second  )
 
elif  operator == "*":
    print( first * second  )
 
elif operator == "**":
    print( first ** second  )
 
elif operator == "/":
    print( first / second  )
 
else:
    print("invalid operator ")
