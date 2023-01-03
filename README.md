# Day1
list=['1','2','3','4','5','6','7','8','9','10','11','12','13','19','15','16','17','18','14','20','21','28','23','24','25','26','27','22','29','30']
print(list) 
print(len(list))
 #to find the length of the list print(len(list))
list[9]="HARI"
print(list)
 #we can assign value 
list.append('37')
print(list)
 #Append to insert element at end position 
list.insert(8,'91')
print(list)
 #insert: to insert element at specified position
list.remove('24')
print(list) 
 #remove:to remove wanted element 
del list[2]
print(list)
 #to del element 
list.pop()
print(list) 
 #pop: to remove element
list.pop(5)
print(list) 
#pop using to remove particular element using index
list.sort() 
#sort() is used to sort elements
print(list)
list.sort(reverse=True)
print(list)
 
