AirBNB

Steps
-Console
-Web static
-MySQL storage
-Web framework
-RESTful API
-Web dynamic

How can I store my instances?
For example;

class Student():
    def __init__(self, name):
        self.name = name

students = []
s = Student("John")
students.append(s)
Here, I’m creating a student and store it in a list. But after this program execution, my Student instance doesn’t exist anymore.

class Student():
    def __init__(self, name):
        self.name = name

