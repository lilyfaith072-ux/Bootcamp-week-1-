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
            print("Grade: Fail")except ValueError:
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


Artificial Intelligence and Machine Learning
Artificial Intelligence (AI) is a branch of computer science that focuses on creating machines capable of performing tasks that normally require human intelligence. These tasks include learning, reasoning, problem-solving, decision-making, understanding language, recognizing images, and interacting with humans. AI systems are designed to imitate human thinking and improve their performance through experience.
Machine Learning (ML) is a subset of Artificial Intelligence. Instead of being explicitly programmed for every task, machine learning enables computers to learn from data and improve their performance automatically. The more data a machine learning model receives, the better it becomes at making predictions or decisions.
One of the major categories of machine learning is supervised learning. In supervised learning, the computer learns using labelled data. This means the input data already contains the correct answers. The algorithm studies the relationship between inputs and outputs so that it can predict the correct output for new data. Examples of supervised learning include email spam detection, predicting house prices, disease diagnosis, and student performance prediction.
Another category is unsupervised learning. In unsupervised learning, the data is not labelled. The computer analyses the data to identify patterns, similarities, and relationships without knowing the correct answers beforehand. It groups similar data together or discovers hidden structures. Examples include customer segmentation in marketing, fraud detection, recommendation systems, and grouping similar documents.
The key difference between supervised and unsupervised learning is that supervised learning uses labelled data with known answers, while unsupervised learning works with unlabelled data to discover hidden patterns. Supervised learning is mainly used for prediction and classification, whereas unsupervised learning is used for clustering and pattern recognition.
Artificial Intelligence has become part of everyday life. One common application is virtual assistants such as Siri, Google Assistant, and Alexa, which can answer questions, set reminders, and perform voice commands. Another example is recommendation systems used by platforms such as Netflix, YouTube, and Spotify to suggest movies, videos, and music based on user preferences.
In healthcare, AI assists doctors in diagnosing diseases by analysing medical images and patient records. It can also help predict diseases early, leading to faster treatment. In banking, AI detects fraudulent transactions, improves customer service through chatbots, and assists in credit scoring.
The transport industry also benefits from AI through self-driving vehicles, intelligent traffic management systems, and route optimisation. Businesses use AI to automate repetitive tasks, analyse customer behaviour, and improve decision-making. In education, AI supports personalised learning by adapting lessons to suit each student's pace and abilities.
Machine learning is also widely used in agriculture to monitor crop health, predict weather conditions, and improve farming productivity. Security systems use facial recognition and fingerprint identification to enhance safety.
Although AI offers many advantages such as increased efficiency, improved accuracy, automation, and better decision-making, it also presents challenges. These include job displacement due to automation, privacy concerns, bias in AI systems, and the high cost of developing advanced AI technologies. Therefore, AI should be developed responsibly and ethically.
In conclusion, Artificial Intelligence and Machine Learning are transforming the world by making systems smarter and more efficient. AI enables machines to imitate human intelligence, while machine learning allows them to learn from data without explicit programming. Understanding these concepts is important because AI continues to influence healthcare, education, finance, transportation, agriculture, and many other industries. As technology advances, AI and machine learning will continue to play an even greater role in solving real-world problems and improving people's lives.

    Python Fundamentals & AI Concepts Assignment

## Student Information

- **Name:** Lilyfaith Wangari
- **Course:** AI & Machine Learning
- **Assignment:** Python Fundamentals Implementation & AI Concepts Documentation

---

# Project Description

This project demonstrates the fundamental concepts of Python programming and basic Artificial Intelligence (AI) concepts. It includes the implementation of Python variables, data types, functions, control structures, loops, and error handling, along with documentation explaining AI and Machine Learning concepts.

---

# Objectives

- Demonstrate understanding of Python fundamentals.
- Apply variables and different data types.
- Create and use custom functions.
- Implement decision-making using if-elif-else statements.
- Use loops to automate repetitive tasks.
- Handle errors using try-except.
- Explain basic Artificial Intelligence and Machine Learning concepts.

---

# Features

- Uses all basic Python data types:
  - Integer
  - Float
  - String
  - Boolean
  - List
  - Dictionary

- Includes:
  - Three custom functions
  - For loop
  - While loop
  - If-elif-else statements
  - Exception handling

---

# Project Structure

```
Project Folder
│
├── main.py
├── AI_Concepts_Report.docx (or PDF)
└── README.md
```

---

# Requirements

- Python 3.x

---

# How to Run the Project

1. Install Python 3 on your computer.
2. Download or clone this repository.
3. Open the project folder in Visual Studio Code or any Python IDE.
4. Run the program using:

```bash
python main.py
```

5. Follow the on-screen menu instructions.

---

# Sample Output

```
===== MENU =====
1. Display Student
2. Calculate Average
3. Show Subjects
4. Exit
```

---

# AI Concepts Covered

- Artificial Intelligence (AI)
- Machine Learning (ML)
- Supervised Learning
- Unsupervised Learning
- Real-world Applications of AI
- Benefits and Challenges of AI

---

# Technologies Used

- Python 3
- Visual Studio Code

---

# Learning Outcomes

After completing this project, I learned how to:

- Use Python variables and data types.
- Write reusable functions.
- Apply loops and conditional statements.
- Handle program errors using exceptions.
- Understand the relationship between Artificial Intelligence and Machine Learning.
- Explain supervised and unsupervised learning with real-world examples.

---

# Author

**Lilyfaith Wangari**

---

# License

This project is submitted for academic purposes only.