# codepro1
while True:

    a=int(input("enter first number\n"))
    b=int(input("enter second number\n"))
    print("choose 1 for addition")
    print("choose 2 for subtraction")
    print("choose 3 for multiplication")
    print("choose 4 for dividion")
    print("close 5 for exit the calculator")

    ch = input("Enter choice between (1-5):\n ")
    if ch== "5":
            print("closing the calculator")
            break
    
    
    if ch in ("1","2","3","4","5"):
        
        if ch == "1":
            print("result for a+b =",a+b)

        elif ch == "2":
            print("result for a-b =",a-b)

        elif ch == "3":
            print("result for a*b =",a*b)

        elif ch == "4":
            print("result for a/b =",a/b)

    else:
        print("the number you entered is not valid")

    c = input("\nto exit the calculator press 5 or press 0 to restart the calculator\n ")

    if c == "5":
            print("closing the calculator\n")
            break
    else :
         print("restarting \n")
