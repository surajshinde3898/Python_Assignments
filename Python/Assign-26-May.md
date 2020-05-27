## write a python program to  sort a list of elements using the bubble sort

l1 = [2,10,9,8,20,15,25,30,28,12,5]

n= len(l1)

for i in range(n):
    
    for j in range(0,n-1):
        
        if l1[j]>l1[j+1]:
            
            l1[j],l1[j+1]= l1[j+1],l1[j]
            
print(l1)


## write a python program for sequential search [Linear Search]

def linear_search(l1,N):

    flag = False
    
    for i in l1:
    
        if i == N:
        
            flag = True
            
            return flag
            
    return flag   
        

l1 = [10,9,8,20,15,25,30,28]

N  = int(input("enter Number to search"))

Bool = linear_search(l1,N)

if Bool == True:

    print("Number is present")
    
else:

    print("Number is not present")


## write a python program for binary search.


def binary_search(arr, low, high, x):

    if high >= low:
    
        mid = (high + low) // 2
        

        if arr[mid] == x:
        
            return mid

        elif arr[mid] > x:
        
            return binary_search(arr, low, mid - 1, x) 

        else:
        
            return binary_search(arr, mid + 1, high, x)

    else:
    
        return -1


arr = [ 2, 3, 4, 10, 40 ]

x = 10

result = binary_search(arr, 0, len(arr)-1, x) 
  
if result != -1:

    print("Element is present at index", str(result))
    
else:

    print("Element is not present in array") 




## write a python program to concatinate two lists index-wise.

list1=['M','na','i','lak']

list2=['y','me','s','han']

list3 =[]

for i in range(0,len(list1)):
    
    for j in range(0,len(list2)):
        
        if i == j:
            
            String=list1[i]+list2[j]
            
            list3.append(String)
            
print(list3)            
            

## iterate a given list and check if a given element already exist in a dictionary as a key value if not delete it from the list

roll_number =[47,64,69,37,76,83,95,97]

sampledict = {'John':47,'Peter':64,'Mahi':37,'Maria':76}

roll_number1=[]

for i in sampledict.values():
    
    for j in range(0,len(roll_number)):
        
        if i == roll_number[j]:
            
            roll_number1.append(roll_number[j])
            
print(roll_number1)           

            
    
        











































