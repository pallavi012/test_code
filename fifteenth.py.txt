def sum_of_even_odd():
    even,odd=0,0
    for i in range(1,101):
        if i % 2 == 0:
            even += i
        elif i%2!=0:
            odd+=i
    print('Sum of even numbers is : ',even)
    print('Sum of odd numbers is : ',odd)
sum_of_even_odd()