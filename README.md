[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15342035&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
  
   - Python is a high level programming language, which is known for its simplification and readability
   - The key feature is that Python is simple and easy to learn, and has extensive standard libraries e.g. Django, Flask, and Pandas.
   - Large community and very simple ecosystem.
   - Python is very effective when it comes to Machine Learning, Data Science, and Web development. 
 

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
  
   - The latest version can be downloaded from Python.org.
   - Run the package, Add to Path, and do with installation and verify by typing "Python -v" in the terminal.
   - To set an environment in Python, Install virtualenv if not already installed: pip install virtualenv.
      Create a virtual environment: python -m venv myenv.
      Activate the virtual environment:
      Windows: myenv\Scripts\activate

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
  
   - Print, is a built-in function that outputs the text in the console.
   -  "Hello, World!", is a string enclosed in quotation.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
  
   - Boolean: True and false statement e.g. nature = true.
   - string: number or words in enclosed quotations e.g. name = "nerd".
   - Integers: real numbers e.g. x = 5.
   - Float: decimal numbers e.g. y = 3.321
   - List: numbers in list format e.g [1, 2, 3, 4] 

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
  
   - boy = 15 if boy > 15:
   - print("boy is young")
   - else:
          print("print is still a child")
  
   - #loop
   - for x in cars: print(x)
  
   - #while loop
   - count = 0
   - while count < 5:
   - print("count")
   - count += 1

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
  
   - Functions are just reusable blocks of code.
   - def multiply(a, b)
   - return a * b:
   - results = (2, 8)
   - print(result)
   - output: 32

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
  
   - Lists are ordered collections of items.
   - Dictionaries are an unordered list of items.
  
   - #List:
   - numbers = [1, 2, 3, 4, 5]
   - numbers.append(7)
   - print(numbers)
   - output: 1, 2, 3, 4, 5, 7
  
   - #Dictionaries:
   - person = {"name": "Kulani", "age": 25}
   - person = ["location": "South Africa"]
   - print(person)
   - output: {"name": 'Kulani', 'age': 25, 'location': 'South Africa'}

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
  
   - Allows you to handle runtime gradually but using 'try', 'except', 'finally'
   - try:
         result = 10 / 0
     except: ZeroDivisiobError:
                               print("You cannot divide by Zero")
     finally:
             ("We can work on this") 

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
  
   - Modules are files containing Python code.
   - Packages are Directories containing multiple modules.
  
   - Import maths
   - print(math.multiplu(2, 8))
   - output: 32

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
   
    - #Reading:
         with open('example.txt', 'r') as file:
         content = file.read()
         print(content)


   - #Writing:
          lines = ["First line", "Second line", "Third line"]
      with open('output.txt', 'w') as file:
        for line in lines:
           file.write(line + "\n")

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


