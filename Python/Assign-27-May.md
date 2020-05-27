## 1
'''

dict1 = {'Suraj':85, 'Shivraj':60, 'Raviraj':55, 'Omkar':65 ,'Rushikesh':90}

dict2 = dict([(value,key) for key , value in dict1.items()])

print("keys: values")

for i in dict2:

    print(i,":",dict2[i],end='')
    
'''

## 2
'''

l1 = [12,52,45,52,65,88]

for i in range (len(l1)):

    mn = i
    
    for j in range(i+1, len(l1)):
    
        if l1[mn]>l1[j]:
        
            mn = j
            
    l1[i],l1[mn]= l1[mn],l1[i]
    

for i in range(len(l1)):

    print("%d" %l1[i])
    
'''


## 3

'''

def insertion_sort(arr):

    for i in range(1, len(arr)):
    
        key = arr[i]
        
        j = i-1
        
        while j>= 0 and key< arr[j]:
        
            arr[j+1] = arr[j]
            
            j -= 1
            
        arr[j+1] = key
        


arr = [43, 56, 12, 98, 57, 22, 44]

sort(arr)

for i in range(len(arr)):

    print("%d" %arr[i])
'''

## 4
'''
L1 = ["a", "b", ["c", ["d", "e", ["f", "g"], "k"], "l"], "m",  "n"]

added = ['H','I','J']

L1[-3][-2][-2].extend(added)

print(L1)

'''

'''
added = ['h','i','j']

L1[2][1][2].extend(added)

print(L1)

'''

## 5

sampleDict = {
    
   "class":{
       
      "student":{
          
         "name":"Mike",
         
         "marks":{
             
            "physics":70,
            
            "history":80
            
         }
      }
   }
}

print(sampleDict['class']['student']['marks']['history'])




















