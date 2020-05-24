#1 you are given with a list of integer elements . Make a new list which will store of elements of previous list.

l1 = [1,2,3,4,5,6,7,8,9,10]

l2=[]

for i in l1:

    sq=i**2
    
    l2.append(sq)

print("l1 list: ",l1)    

print("square of l1 list: ",l2)

#2 From a list containing ints , strings and float , makes three lists to store them separatly.

l1 =  [1,2,3,"Hello","Suraj",2.56,986.87]

int_list=[]

string_list=[]

float_list=[]


for i in l1:

    if type(i) == int:
    
        int_list.append(i)
        
    elif type(i) == float:
    
        float_list.append(i)
        
    else:
    
        string_list.append(i)
        
print(int_list)

print(float_list)

print(string_list)


#3 print the pattern

for i in range(1,6):

    for j in range(1,i+1):
    
        print(j,end='')
        
    print("")    
        


#4 Addition of 3*3 matrix

import numpy as np

l1=[]

l2=[]

N=int(input("enter no. of inputs"))

for i in range(1,N+1):

    element = int(input("enter elements in 1st Array"))
    
    l1.append(element)
    
for j in range(1,N+1):

    element = int(input("enter elements in 2nd Array"))
    
    l2.append(element)
    
arr1 = np.array(l1)

arr2 = np.array(l2)

arr1 =arr1.reshape(3,3)

arr2 =arr2.reshape(3,3)

print(arr1)

print(arr2)

add = [[arr1[i][j]+arr2[i][j] for j in range(len(arr1[0]))] for i in range(len(arr1))]

for k in add:

    print(k)


#5 Narcissistic Number

N=int(input("enter numbe"))

S=0

Count = 0

temp1 = N

temp2 = N

while N!=0:

    R=N%10
    
    N=N//10
    
    Count+=1
    
while temp1!=0:

    R=temp1%10
    
    S=S+(R**Count)
    
    temp1=temp1//10    

if S == temp2:

    print(temp2,"is narcisstic")
    
else:

    print(temp2,"is not narcisstic")








