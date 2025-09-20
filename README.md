# Task 1
Takes input from the user

a = int(input("Enter the First Name: "))


input() asks the user to type a value.

int() converts it into an integer (number).

Example: If user enters 7, then a = 7.

⚠️ Note: The prompt "Enter the First Name:" is misleading because here we are asking for a number, not a name. It should be "Enter a number:".

Checks divisibility by 2

if a % 2 == 0:


% is the modulus operator, it gives the remainder.

If a number divided by 2 gives remainder 0, it’s even.

Example:

8 % 2 = 0 → Even

7 % 2 = 1 → Odd

Decision making with if-else

If condition (a % 2 == 0) is true → print "Number is Even."

Otherwise → print "Number is Odd."

✅ Example Run
Enter a number: 10
Number is Even.

# Task 2
Create a list of numbers from 1 to 50

a = list(range(1, 51))


range(1, 51) generates numbers starting from 1 up to 50 (51 is excluded).

list() converts that range into a list.

So, a = [1, 2, 3, ..., 50].

Initialize counter

count = 0


Variable count will store the sum.

Starts at 0.

Loop through the list and add numbers

for i in a:
    count = count + i


The for loop goes through each number in list a.

Each number is added to count.

After full loop, count holds the total sum.

Example (first few steps):

Initially count = 0

i = 1 → count = 0 + 1 = 1

i = 2 → count = 1 + 2 = 3

i = 3 → count = 3 + 3 = 6

… continues until i = 50.

Print the result

print("The Sum of Numbers from 1 to 50 is : ", count)


Final output:

The Sum of Numbers from 1 to 50 is :  1275


Enter a number: 7
Number is Odd.
