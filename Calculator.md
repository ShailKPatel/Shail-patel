#calculator

#input
N1 = int(input("Enter first number:"))
N2 = input("Enter operator:")
N3 = int(input("Enter second number:"))

#calculation

if N2=="+":
    print(N1+N3)
    
elif N2=="-":
    print(N1-N3)
    
elif N2=="*":
    print(N1*N3)
    
elif N2=="/":
    print(N1/N3)
    
else:
    print("U SUCK!!!")
