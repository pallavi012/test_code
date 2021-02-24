def sum_of_odds():
    a=int(input("Enter range to find sum of odd in that range : "))
    sum=0
    for i in range(1,a+1):
        if i%2!=0:
            sum+=i
    print(sum)
sum_of_odds()