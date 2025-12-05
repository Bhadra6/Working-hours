ovpay=0
sum=0
for i in range(1,11):
    print("Enter Working Hours of Emp",i,":")
    h=int(input())
    if(h>40):
        extra=h-40
        ovpay=extra*12
        print("Over time pay of emp",i,"is",ovpay)
        sum=sum+ovpay
    else:
        print("No Overtime Pay")
print("Total Overtime Pay of all employees:",sum)







OUTPUT:
Enter Working Hours of Emp 1 :
23
No Overtime Pay
Enter Working Hours of Emp 2 :
44
Over time pay of emp 2 is 48
Enter Working Hours of Emp 3 :
23
No Overtime Pay
Enter Working Hours of Emp 4 :
45
Over time pay of emp 4 is 60
Enter Working Hours of Emp 5 :
67
Over time pay of emp 5 is 324
Enter Working Hours of Emp 6 :
78
Over time pay of emp 6 is 456
Enter Working Hours of Emp 7 :
2
No Overtime Pay
Enter Working Hours of Emp 8 :
3
No Overtime Pay
Enter Working Hours of Emp 9 :
48
Over time pay of emp 9 is 96
