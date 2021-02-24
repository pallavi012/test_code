def reverse_list_numbers(l):
    new_list=[]
    for i in reversed(l):
        new_list.append(i)
    print('Original list :',l,'\nAfter reverse list is :',new_list)
def reverse_list_string(m):
    new_list1=[]
    for i in reversed(m):
        new_list1.append(i)
    print('Original list :',m,'\nAfter reverse list is :',new_list1)
l = [1, 2, 3, 4, 5]
m = ["A", "B", "C", "D"]
reverse_list_numbers(l)
reverse_list_string(m)