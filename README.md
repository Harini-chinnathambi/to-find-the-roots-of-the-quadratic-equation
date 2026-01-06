import math
a=float(input("enter the first coefficient:"))
b=float(input("enter the second coefficient:"))
c=float(input("enter the third coefficient:"))
if(a!=0.0):
    d=(b*b)-(4*a*c)
    if(d==0.0):
        print("the roots are real and equal")
        r=-b/(2*a)
        print("the roots are","r","and",r)
    elif(d>0.0):
            print("the roots are real and distinct")
            r2=(-b-(math.sqrt(d)))/(2*a)
            print("the roots is:",r1)
            print("the roots is:",r2)
    else:
                print("the roots are imaginary.")
                rp=-b/(2*a)
                ip=math.sqrt(-d)/(2*a)
                print("the root1 is:",rp,"+i",ip)
                print("the root2 is:",rp,"-i",ip)
else:
                    print("not a quadratic equation")
            
output:
enter the first coefficient:2
enter the second coefficient:4
enter the third coefficient:6
the roots are imaginary.
the root1 is: -1.0 +i 1.4142135623730951
the root2 is: -1.0 -i 1.4142135623730951


