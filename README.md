# class-and-objects
from datetime import date
class Employee:
    def __init__(self,name,dob,gender,year_joining,city):
        self.name = name
        self.dob = dob
        self.gender = gender
        self.year_joining = year_joining
        self.city = city
        
    def address(self):
        addr = f"Name : {self.name}\nDOB : {self.dob}\ngender : {gender}\nYear_joining : {year_joining}\ncity : {city}"
        return addr
        
    def age(self):
        current_year = date.today().year
        return current_year = self.dob
        
emp1 = Employee("virat",1998,male,2020,"Chennai")
emp2 = Employee("kohil",1999,male,2021,"vellore")
emp3 = Employee("kavi",1998,female,2021,"kovai")
 
print(emp1.address())
print(emp2.adress())
print(emp3.adress())
 
