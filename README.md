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

