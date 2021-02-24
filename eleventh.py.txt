def add_item(food_staff,b):
    a=[]
    for i in food_staff:
        a.append(i)
    a.append(b)
    print(a)
def add_item(numbers,b):
    a=[]
    for i in numbers:
        a.append(i)
    a.append(b)
    print(a)

food_staff = ['Potato', 'Tomato', 'Mango', 'Milk']
numbers = [2, 3, 7, 9]
add_item(food_staff,input("Enter item you want to add : "))
add_item(numbers,int(input("Enter number you want to add : ")))