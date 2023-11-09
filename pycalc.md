def Addition(A,B):
    Sum = A + B
    print(str(A)+ "+"+ str(B) + "=" + str(Sum))
    return sum
def Subtraction(A,B):
    Dif = A-B
    print(str(A)+ "-"+ str(B) + "=" + str(Dif))
    return Dif
def Multiplication(A,B):
    Mut = A * B
    print(str(A)+ "*"+ str(B) + "=" + str(Mut))
    return sum
def Division(A,B):
    Div = A/B
    print(str(A)+ "/"+ str(B) + "=" + str(Div))
    return sum
while True:
    print("A for Addition")
    print("S for Subtraction")
    print("M for multiplication")
    print("D for division")
    print("Q for Quit")
    choice = ["A","S","C","D","Q"]

    Operation = input("Type your preffered operation " ).upper()


    if Operation == choice[0]:
        A = int(input("Enter first value: "))
        B = int(input("Enter Second value: "))
        Addition(A,B)
    elif Operation == choice[1]:
        A = int(input("Enter first value: "))
        B = int(input("Enter Second value: "))
        Subtraction(A,B)
    elif Operation == choice[2]:
        A = int(input("Enter first value: "))
        B = int(input("Enter Second value: "))
        Multiplication(A,B)
    elif Operation == choice[3]:
        A = int(input("Enter first value: "))
        B = int(input("Enter Second value: "))
        Division(A,B)
    elif Operation == choice[4]:
        print("Program Ended")
        quit()

    elif Operation != choice:
        print("Enter a valid operation")
