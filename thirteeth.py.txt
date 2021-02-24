def sum_of_numbers():
    a=int(input("Enter any Number  : "))
    sum=0
    for i in range(1,a+1):
        sum+=i
    print("sum of numbers is : ",sum)
sum_of_numbers()