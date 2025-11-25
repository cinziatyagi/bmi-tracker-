BMI Calculator
📌 Overview
This project is a simple BMI (Body Mass Index) Calculator written in Python.
It takes a user’s height (in centimeters) and weight (in kilograms) as input and calculates their BMI.
Based on the BMI value, the program categorizes the user as:
	Underweight
	Healthy
	Overweight
	Obese
This project demonstrates the use of:
	User input handling
	Basic arithmetic operations
	Conditional statements (if, elif, else)
	Simple health-based classification logic
________________________________________
🚀 Features
	Accepts user input for height and weight
	Calculates BMI using the formula:
BMI = weight (kg) ÷ (height in meters)²
	Displays calculated BMI
	Classifies BMI into health categories
	Beginner-friendly and easy to understand
________________________________________
🧮 BMI Formula Used
The formula implemented in this project is:
BMI = weight(in kg)/(height(in cms)/100)^2 
Height is divided by 100 to convert cm to meters, because BMI requires height in meters.
________________________________________
📂 Project Code
the_height = float(input("Enter the height in cm: "))  
the_weight = float(input("Enter the weight in kg: "))  
# defining a function for BMI  
the_BMI = the_weight / (the_height/100)**2  
# printing the BMI  
print("Your Body Mass Index is", the_BMI)  
# using the if-elif-else conditions  
if the_BMI <= 18.5:  
    print("Oops! You are underweight.")  
elif the_BMI <= 24.9:  
    print("Awesome! You are healthy.")  
elif the_BMI <= 29.9:  
    print("Eee! You are over weight.")  
else:  
    print("Seesh! You are obese.")  
________________________________________
📝 How to Run
	Install Python (if not already installed).
	Save the script as bmi_calculator.py (or any name).
	Open a terminal or command prompt.
	Run the script using:
python bmi_calculator.py
	Enter your height and weight when prompted.
________________________________________
📊 BMI Categories
BMI Range	Category
≤ 18.5	Underweight
18.6 – 24.9	Healthy
25 – 29.9	Overweight
≥ 30	Obese
________________________________________
📸 Screenshots
 
________________________________________
🎯 Future Enhancements
	GUI-based BMI calculator
	Support for feet/inches input
	Error handling for invalid inputs
	Health tips based on BMI category
# bmi-tracker-
