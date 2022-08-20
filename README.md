# faulty-cauculator
print('welcome to calcultor')
print('please enter the two numbers ')
num1=int(input())
num2=int(input())
if num1==45 and num2==3:
    print('please specify the operatio needs to be done \n' '1. add \n' '2.sub\n''3.mul\n')
    l=input()
    print(555)
elif num1==56 and num2==9:
    print('please specify the operatio needs to be done \n' '1. add \n' '2.sub\n''3.mul\n')
    l = input()
    print(77)
elif num1==56 and num2==6:
    print('please specify the operatio needs to be done \n' '1. add \n' '2.sub\n''3.mul\n')
    l = input()
    print(4)

else :
    print('please specify the operatio needs to be done \n' '1. add \n' '2.sub\n''3.mul\n')
    op=input()

    if op=='add':
        print(num1+num2)
    elif op=='sub':
        print(num1-num2)
    elif op=='mul':
        print(num1*num2)
    else :
        print(num1/num2)
