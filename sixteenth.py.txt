fruit_list=['banana', 'orange', 'mango', 'lemon']
print("original list is :\n",fruit_list)
for i in range(0,len(fruit_list)):
    for j in range(0,i+1):
        temp=fruit_list[i]
        fruit_list[i]=fruit_list[j]
        fruit_list[j]=temp
print("List after reversing the order :\n",fruit_list)
