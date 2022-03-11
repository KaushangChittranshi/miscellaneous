# miscellaneous
Extra codes that I have tried

Question:Write the pyhton program to store costs 2000,3000,4000 into three variables there P1,P2,P3 calculate total bill store
into one variable called total bill 30% discount and 40% tax finally display the total bill after the discount and tax with the messages on wearable
implement this by using four steps:

 P1= 2000
 p2=3000
 P3=4000
 totbill=P1+P2+P3
 print('Total bill is :',totbill )
 disc=totbill*0.3
 totabill=totbill-disc
 print('Bill with discount:',totabill )
 tax=totabill*0.4
 totalbill=totabill+tax
 print('Your total bill is :',totalbill)


 Question 2:
 P1=1000 on P1 10% discount, P2=2000 on P2 20% disocunt. Calculate the total bill 30% discount on the total bill 40% tax on the total bill after tax.
 
P1=1000
P2=2000
DiscP1=P1*0.1
DiscP2=P2*0.2
totbill=(P1-DiscP1)+(P2-DiscP2)
print('Bill with internal dsicount is :',totbill)
Disc=totbill*0.3
totabill=totbill-Disc
print('Bill with overall discount :', totabill)
tax=totabill*0.4
totalbill=tax+totabill
print('Total bill with tax :',totalbill)
p1=1000
p2=2000
p1disc=p1*0.1
p1=p1-p1disc
p2disc=p2*0.2
p2=p2-p2disc
p1tax=p1*0.2
P1=p1+p1tax
p2tax=p2*0.3
P2=p2+p2tax
totalbill=P1+P2
print('Totalbill is :',totalbill)

Ques == GRADING SYSTEM

print("write your marks in english,hindi,maths,science,social science respectively")
a=int(input())
b=int(input())
c=int(input())
d=int(input())
e=int(input())
print("your total marks are",int(a+b+c+d+e))
p=int((a+b+c+d+e)/5 )
print("your percentage is",p)
if p>=80 : print ('you achieved A grade')
elif p>=60 : print('you achieved B grade')
elif p>=40 : print('you achieved C grade')
else  : print ('you achieved D grade GO STUDY')

#   ====================================== finding max between three numbers
a=int(input('enter your number=' ))
b=int(input('enter your number=' ))
c=int(input('enter your number=' ))
if b>a>c or c>a>b:
    print('a is middle value')
elif a>b>c or c>b>a:
    print('b is middle value ')
else:
    print('c is middle value')
#===================================== finding middle value between three
#while(control statement) loop has three parts : 1. initialization: i=1 ;; 2. condition: i<=10 ;; 3. increment or decrement: i=i+1
a=1          # initialization
#while(a<=10) :  # condition
#    print(a,end=' ' )  # extra spaces tell that these two condition are under while statement
#    a=a+1    # increment or decrement
# write a program to print number from 1 to n(user input)

#n = int(input('enter your number upto which you want::'))
#i=1

#while(i<=n):
#    print(i,end="  ")
#    i=i+1
#i=10
#while(i>=1):
#    print(i, end="  ")
#    i=i-1
#n=int(input("\n enter the number upto which u want="))
#i=1
#while(i<=n):
#    print(i,end="  ")
#    i = i + 1
  # =====program to find the sum of 1to n=============================================
#n=int(input('enter your number='))
#i=1
#sum=0
#while(i<=n):
#    sum=sum+i # used fro add unitl it excedes the given value
#    i=i+1
#print('sum is',sum)
#====program to find the sum of square or cube of n natural number ===============================
#n=int(input('enter the number'))
#i=1
#sum=0
#while(i<=n):
#    sum=sum+(i*i)
#    i=i+1
#print("sum is=" ,sum)
#========program to print n even natural numbers====================
#n=int(input('enter your number='))
#i=2
#while(i<=n):
#    print(i, end="  ")
#    i=i+2
#===============program to print the sum of even natural numbers==========
#n=int(input('enter your number='))
#i=2
#sum=0 # initialized
#while(i<=n):
#    sum=sum+i # phele sum=0+2=2 phir i ki value increase karegi jo hogi 4 aur phir wo loop kar le jayega cond. mein aur check karega ayr phir wapas condition start hogi
#              #sum=2+4=6 aur i=4+2 =6 and it continues
#    i=i+2 #dono conditions ek saath loop karenge
#print('sum of the numbers is', sum)

#====================program to find the sum of even natural numbers from 1 to n =====================
#n=int(input('enter your number='))
#i=1
#sum=0
#while(i<=n):
#    if (i%2)==0:
#        sum=sum+i # indentation kept in mind
#    i=i+1
#print('sum of the even numbers is', sum)

#=============== program to find the sum of n even numbers (ex 4 even numbers) ==============
#n=int(input('how many numbers you what to add'))
#i=1
#sum=0 # sum variable ko set kiya 0 pe
#count=0 # count variable for counting
#while(count<n): # n baar loop chalana hai aur = sign nahi hoga nahi toh wo n+1 times chal jayega
#    if(i%2==0):
#        sum=sum+i
#        count=count+1
#    i=i+1 # ye if ka part nahi hai
#print('sum of the numbers is ', sum) #watch lecture #20

#level 2=========================program to find the sum of the of digits of the given number
#i=int(input('enter the number for which you the sum='))
#sum=0
#while(i>0):
#    sum=sum+(i%10)
#    i=i//10
#print('sum of the digits= ', sum)

# =============================program to find the sum of th square of the digits of the given number===========
#i=int(input('enter the number for which you the sum='))
#sum=0
#while(i>0):
#    sum=sum+(i%10)*(i%10)
#    i=i//10
#print('sum of the digits= ', sum)

# armstrng no. = for ex 153 ...  1^3+2^3+3^3 = 153 or 1234... 1^4+ 2^4+ 3^4+ 4^4= 1234
# sum of the no. to the times of the digits is that same number

#====================check whether the no. is armstrong number or not======================
#i=int(input('enter the number for which you the sum='))
#orig=i # kyunki i har bar apni lose kar leta hain kyunki i=i//10 ki condtion ki wajah se
#sum=0
#while(i>0):
#    sum=sum+(i%10)*(i%10)*(i%10)
#    i=i//10
##if orig==sum:
#    print('the no. is armstrong no.')
#else:
#    print('it is not an armstrong no.')

 #======================program to fing wether the no. is armstrong no. or not===========
#n=int(input('enter the number='))
#i=n
#count=0
#while(i>0):
#    i=i//10
#    count=(count+1) # yhan tak digits count ho jyege
#sum=0
#i=n
#while(i>0):
#    digit=i%10
#    x=1
#    prod=1
 #   while(x<=count):
 #       prod=prod*digit
 #       x=x+1
#    sum=sum+prod
#    i=i//10
#if (sum==n):
#    print('it is armstrong')
#else:
#    print('not armstrong')

#==================program, to find the products of the given number===================
#i=int(input('enter the number to find the product'))
#prod=1
#while(i>0):
#    prod=prod*(i%10)
#    i=i//10
#print('prod of the digits is', prod)

#=====================program to find the reverse of the given number================
#i=int(input('enter the number'))
#rev=0
#while(i>0):
#    rev=(rev*10)+i%10
#    i=i//10
#print('reverse of the number is ', rev)

#==============palindrome is the number which after being reversed yields the same number ex: 535 = 535 =================
#==============program to print the palindrome numbers===============

#i=int(input('enter the number to checked as palindrome number='))
#x=i
#rev=0
#while(i>0):
#    rev=(rev*10)+i%10
#    i=i//10
#if(x==rev):
#    print('value is palindrome')
#else:
#    print('value is not palindrome')

#==================check whether the number is prime or not=============
#loop ko jana hoga 1 to prime numbe rto be checked

#n=int(input('enter the number to checked='))
#count=0
#i=1
#while(i<=n):
#    if(n%i==0):
#        count=count+1
#    i=i+1
#if (count==2): print('the number is prime ')
#else: print('the number is composite')

# ==================print the factorial of the given number===========
#i=int(input('enter the given number = '))
#fac=1
#while(i>0):
#    fac=fac*i
#    i=i-1
#print('factorial of the given number is = ', fac)

#=================print the fibonacci sequence ( add of the two before numbers==========
#n=int(input('enter your number='))
#x=0
#y=1
#z=0
#while(z<=n):
#    print(z,end=" ")
#    x=y
#    y=z
#    z=x+y
