# Interactive Quiz Game

## Overview

The Interactive Quiz Game is a Java-based application that allows users to participate in a quiz through an interactive command-line interface. The program supports different types of questions and evaluates user responses to provide a final score.

This project was developed to practice object-oriented programming concepts in Java, including class design, inheritance, polymorphism, and object interaction.

---

## Features

- Interactive quiz experience through the console
- Supports multiple question types
- Displays questions and answer choices
- Accepts and validates user answers
- Calculates final quiz score
- Provides feedback based on user performance
- Organized using object-oriented design principles

---

## Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Command-Line Interface (CLI)

---

## Project Structure

```
InteractiveQuizGame
│
├── Question.java                 # Abstract/base class for quiz questions
├── BasicQuestion.java             # Represents standard quiz questions
├── MultipleChoiceQuestion.java    # Represents multiple-choice questions
├── Quiz.java                      # Manages quiz questions and scoring
└── InteractiveQuizGame.java       # Main program and user interaction
```

---

## Object-Oriented Concepts Practiced

This project demonstrates:

- **Classes and Objects**  
  Creating reusable components to represent questions and quizzes.

- **Inheritance**  
  Extending the base `Question` class to create different question types.

- **Polymorphism**  
  Allowing different question objects to behave differently through shared methods.

- **Encapsulation**  
  Protecting data and controlling access through methods.

- **Array/List Management**  
  Storing and managing collections of quiz questions.

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/InteractiveQuizGame.git
```

### 2. Navigate to the project folder

```bash
cd InteractiveQuizGame
```

### 3. Compile the Java files

```bash
javac *.java
```

### 4. Run the program

```bash
java InteractiveQuizGame
```

---

## Example Gameplay

```
Welcome to the Interactive Quiz Game!

Question 1:
What is the capital of France?

A. London
B. Paris
C. Rome
D. Madrid

Your answer: B

Correct!

Final Score: 5/5
```

---

## Future Improvements

Possible enhancements include:

- Adding more question categories
- Adding a timer for each question
- Saving high scores
- Creating a graphical user interface (GUI)
- Loading questions from external files
- Adding user profiles and progress tracking

---

## Author

Created by **Homaira Mohammadi**
