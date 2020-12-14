# Positive_in_list
x = int(input("Enter limit of List : "))
lst = []
i = 1
print("Enter Numbers : ")
for i in range(x):
    y = int(input())
    lst.append(y)
    
for i in lst:
    if i >=0:
        print(i,end=" ")

