A simple Python program to create a Student Grade Calculator.

# Student Grade Calculator

print("----- Student Grade Calculator -----")

name = input("Enter student name: ")

# Taking marks for 5 subjects
m1 = int(input("Enter marks for Subject 1: "))
m2 = int(input("Enter marks for Subject 2: "))
m3 = int(input("Enter marks for Subject 3: "))
m4 = int(input("Enter marks for Subject 4: "))
m5 = int(input("Enter marks for Subject 5: "))

total = m1 + m2 + m3 + m4 + m5
average = total / 5

# Grade calculation
if average >= 90:
    grade = "A+"
elif average >= 75:
    grade = "A"
elif average >= 60:
    grade = "B"
elif average >= 50:
    grade = "C"
else:
    grade = "Fail"

print("\n----- Result -----")
print("Student Name:", name)
print("Total Marks:", total)
print("Average:", average)
print("Grade:", grade)
