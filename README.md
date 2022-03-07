# 5_class
Create a class Class. The __init__ method should receive the name of the class. Each class should also have 2 empty lists - students and grades. Create a class attribute __students_count equal to 22. The class should also have 3 additional methods:
•	add_student(name: str, grade: float) - adds the student and the grade in the two lists if there is free space in the class
•	get_average_grade() - returns the average of all existing grades formatted to the second decimal point (as a number)
•	__repr__ - returns the string (single line):
"The students in {class_name}: {students}. Average grade: {average_grade}". 
The students must be separated by a comma and a space: ", ".
