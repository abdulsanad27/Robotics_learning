# Robotics_learning
Python Programing  

Python Learning Notebook – For Robotics Engineering 

 

Why Python in Robotics? 

Imagine a robot that needs to identify a person and follow them. 

Different technologies work together: 

Python can connect different software components and process data coming from sensors. 

 

Variables 

What is a variable? 

A variable is a name used to refer to a value stored in memory. 

Example: robot_speed = 50 , robot_name = "Humanoid".. 

 

Dynamic Typing 

The same variable name can refer to different types of values at different times.This is called dynamic typing. 

Example: 

 data = 100  -> print(type(data))-> <class 'int'> 

data = "robot"-> print(type(data))-> <class 'str'> 

Data Types 

A data type tells Python what kind of value is being represented. 

1 Integer (int):- Stores whole numbers. 

2 Float :- Stores decimal numbers. 

3 String (str):- Stores text. 

4 Boolean (bool):- Stores either: “True” or “False” 

5 None:- None represents the absence of a value. 

6 Type Conversion:- Sometimes we receive data in one type but need another type. 

Example: 

distance = "25" -> print(type(distance)) ->  <class 'str'> 

distance = int(distance) -> print(type(distance)) -> <class 'int'> 

Robotics Example: - Suppose sensor data arrives as text:  sensor_data = "45.7" 

					    distance = float(sensor_data) 

    print(distance + 10)  = 55.7	<- int type  

Operators 

1 Arithmetic Operators 

Operator 
	

Meaning 
	

Example 

+ 
	

Addition 
	

10 + 5 

- 
	

Subtraction 
	

10 - 5 

* 
	

Multiplication 
	

10 * 5 

/ 
	

Division 
	

10 / 5 

// 
	

Floor division 
	

10 // 3 

% 
	

Modulus 
	

10 % 3 

** 
	

Power 
	

2 ** 3 