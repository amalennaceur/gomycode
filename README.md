# gomycode
checkpoint1
#ex1
liste=[]
i=2000       
while i <=3200:
       if i % 7 == 0 and i % 5 != 0 :
        liste.append(i)
       i+=1   
print(liste)

#ex2
n=int(input("donner un nombre "))
a=1
for i in range (1,n+1) :
  a=i*a
print(a)
    
#ex3
n=int(input("donner un nombre"))
for i in range (1,n+1):
 multiple[i]=i*i
print(multiple)

#ex4
ch=str(input("donner une chaine de caractère"))
n=int(input("donner un entier"))
if n<=len(ch):
 ch=ch[:n]+ch[n+1:]
print(ch)

#ex5
import numpy as np
x= np.arange(6).reshape(3, 2)
print("Original array elements:")
print(x)
print("Array to list:")
print(x.tolist()) 

#ex6
import numpy as np
x = np.array([0, 1, 2])
y = np.array([2, 1, 0])
print("\nOriginal array1:")
print(x)
print("\nOriginal array2:")
print(y)
print("\nCovariance matrix of the said arrays:\n",np.cov(x, y))

#ex7
import math

C= 50
H = 30
D1 = []
result =[]
D0=input("enter the value of D\n")
D1=D0.split(",")
D1 = [int(i) for i in D1]
i=0
l = len(D1)
while(i<l):
    Q = round(math.sqrt((2*C*D1[i])/H))
    result. append(Q)
    i+=1
print("output=",result)
