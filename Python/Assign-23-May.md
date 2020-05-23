#1

N = int(input("Enter Number"))

sum1=0

for i in range(1,N+1):

    sum1=sum1+i
    
    print(i,end='')
    
    if i<N:
    
        print("+",end="")
        
    
print("=",sum1)



#2

Number = (1,2,3,4,5,6,7,8,9)

even = 0

odd = 0

for i in Number:

    if i%2==0:
    
        even+=1
        
    else:
    
        odd+=1
        
print("Number of even numbers:",even)

print("Number of odd numbers:",odd)


#3

for i in range(1,11):

    for j in range(1,11):
    
        print(i*j)
        
    print("\n")


#4

N= int(input("Enter Row Number"))

if N==1:

    print(1)
    
elif N==2:

    print(2**3)
    
elif N==3:

    print(3**3)
    
elif N==4:

    print(4**3)
    
elif N==5:

    print(5**3)





#5

n=int(input("enter number of rows"))

for i in range(1,n+1):

    for j in range(1,i+1):
    
        print(i,end='')
        
    print("\n")    
        






















































