@@@mystry-problem

###Write a program that receives one input, an integer, calculates the factorial of the input and prints it.
code:
num=int(input())
fact=1
for i in range(1,num+1):
    fact *= i

print(fact)


###Create a function named print_range that takes three parameters:
###Range function loop
    start - the starting number (inclusive)
    end - the ending number (exclusive)
    step - the increment value

The function should print all numbers from start to end (not including end) with the given step increment, each on a new line.

code:
def print_range(start, end, step):
      for i in range(start,end,step):
        print(i)

start = int(input())
end = int(input())
step = int(input())

print_range(start, end, step)

