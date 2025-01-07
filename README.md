# codsoft3
calculator
print("welcome to calculator")
while True:
    a = int(input("enter num 1: "))
    b = int(input("enter num 2: "))
    add = a + b
    sub = a - b
    mul = a * b
    if b==0:
        print("this isnt possible")
    else :
        div=a/b
   
    print("enter any operation")
    print("1.ADDITION")
    print("2.SUBTRACTION")
    print("3.MULTIPLICATION")
    print("4.DIVISION")
    print("5.exit")
    operation = int(input("enter the option(1-5): "))
    if operation == 1:
        print("your annswer is: ", add)
    elif operation == 2:
        print("your answer is : ", sub)
    elif operation == 3:
        print("your answer is: ", mul)
    elif operation == 4:
        print("your answer is: ", div)
    elif operation == 5:
        print("goodbye see you again")
        break
    else:
        print("enter valid option!!!")

