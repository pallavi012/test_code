def capitalize_list_item(m):
    new_list1=[]
    for i in m:
        a=i.upper()
        new_list1.append(a)
    print('Original list :',m,'\nAfter reverse list is :',new_list1)
m = ["red", "blue", "white", "orange"]
capitalize_list_item(m)