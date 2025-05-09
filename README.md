# python9
swap operations
#swaping numbers
a=22
b=33
print("before swapping",a,b)
a,b=b,a
print("after swapping",a,b)


#swaping numbers(touple swaping)
a=22
b=33
print("before swapping",a,b)
a,b=b,a
print("after swapping",a,b)


#swaping by temp variable(universal swap)
a=int(input("enter value of a"))
b=int(input("enter value of b"))
print("before swap:",a,b)
temp=a
a=b
b temp
print("after swap:"a,b)


#swap by using arthematic operators
a=int(input("enter value of a:"))
b=int(input("enter value of b:"))
print("before swap",a,b)
a=a+b
b=a-b
a=a-b
print("after swap",a,b)


#swap using symbols
a=int(input("enter value of a:"))
b=int(input("enter value of b:"))
print("before swap",a,b)
a=a*b
b=a/b
a=a/b
print("after swap",round(a),(b))


#by using laogical oper swap
a=int(input("enter value of a:"))
b=int(input("enter value of b:"))
print("before swap",a,b)
a=a^b
b=a^b
a=a^b
print("after swap",a,b)
