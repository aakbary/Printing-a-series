# Printing a series
 This code is used to print a series of numbers
user_input=input("Enter a number: ")
user_input=int(user_input)
def series(n):
  n1=0
  n2=1
  count=0
  while n<=0:
    print("Please enter a positive integer.")
    break
  while count<n:
    print(n1)
    nth=n1+n2
    n1=n2
    n2=nth
    count=count+1
series(user_input)
