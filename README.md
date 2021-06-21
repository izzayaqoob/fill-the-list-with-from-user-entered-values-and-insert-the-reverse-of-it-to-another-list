# fill-the-list-with-from-user-entered-values-and-insert-the-reverse-of-it-to-another-list
list=[]
list1=[]
for i in range(0,10,1):
    list.append(input('Enter values: '))
print('List 1 ',list)

i=9

while i>=0:
    list1.append(list[i])
    i=i-1
print('List 2 ',list1)



