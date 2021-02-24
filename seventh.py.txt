l=[]
m=[]
for i in range(1,101):
	if i%2==0 :
		l.append(i)
	elif i%2!=0:
		m.append(i)
print('List of even numbers is :\n',l)
print('List of odd  numbers is :\n',m)