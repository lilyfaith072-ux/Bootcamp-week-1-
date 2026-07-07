# Bootcamp-week-1-
# Python Fundamentals Project

# Variables and Data Types
student_name = "Lilyfaith"
age = 21                  # Integer
height = 1.65             # Float
is_student = True         # Boolean
subjects = ["Python", "AI", "Machine Learning"]  # List

student = {
    "Name": student_name,
    "Age": age,
    "Height": height,
    "Student": is_student
}

# Function 1
def display_student():
    print("\nStudent Information")
    for key, value in student.items():
        print(f"{key}: {value}")

# Function 2
def calculate_average():
    marks = []
    try:
        for i in range(3):
            mark = float(input(f"Enter mark {i+1}: "))
            marks.append(mark)

        average = sum(marks) / len(marks)
        print("Average =", average)

        if average >= 70:
            print("Grade: A")
        elif average >= 60:
            print("Grade: B")
        elif average >= 50:
            print("Grade: C")
        else:
            print("Grade: Fail")

    except ValueError:
        print("Error: Please enter numbers only.")

# Function 3
def show_subjects():
    print("\nSubjects")
    for subject in subjects:
        print(subject)

# Main Program
while True:
    print("\n===== MENU =====")
    print("1. Display Student")
    print("2. Calculate Average")
    print("3. Show Subjects")
    print("4. Exit")

    choice = input("Choose an option: ")

    if choice == "1":
        display_student()
    elif choice == "2":
        calculate_average()
    elif choice == "3":
        show_subjects()
    elif choice == "4":
        print("Program Ended.")
        break
    else:
        print("Invalid choice.")