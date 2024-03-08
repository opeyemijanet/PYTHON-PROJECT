# PYTHON-PROJECT
BMI CALCULATOR WITH PYTHON

### Project overview

This Python-based BMI (Body Mass Index) calculator is a simple yet powerful tool designed to help individuals assess their body mass index, a key indicator of overall health. Whether you're on a fitness journey, a healthcare professional, or simply curious about your BMI, this calculator provides a user-friendly interface for quick and accurate calculations.

### Data Sources

Personal data

### Tools

Jupyter server

### code

name = input("enter your name: ")

weight = int(input("enter your weight in pounds: "))

height = int(input("enter your height in inches: "))

BMI = (weight * 703) / (height * height)

print(BMI)

if BMI>0:

    if(BMI<18.5):
    
        print(name +", you are underweight.")
        
    elif (BMI<24.9):
    
        print(name +", your weight is normal.")
        
    elif (BMI<29.9):
    
        print(name +", you are overweight.")
        
    elif (BMI<34.9):
    
        print(name +", you are obese.")
        
    elif (BMI<39.9):
    
        print(name +", you are severely obese.")
        
    else:
        print(name +", you are morbidly obese.")
else:

    print("enter valid input")
