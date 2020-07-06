# Inheritance 

#### A concept related to the object oriented approach of programming.

This file will demonstrate how inheritance allows child classes to adopt the methods and functionality available
in its parent class and adding any additional functionality on top. This helps reduce the amount of duplicated code
as it is bad practice to keep repeating yourself. According to the **DRY** acronym, _"Do not repeat yourself."_

[**devops_student**](devops_student.py) **[Parent/ Base Class]**
* **Attributes**
    * current_grade `private`
    * current_trainer `public`
* **Methods**
    * print_details `public`
    * change_current_grade `private` 

[**student_data**](student_data.py) **[Child/ Derived Class]**

The student_data class has actually not got any unique methods of attributes, for the purpose of
demonstrating inheritance, the child class has been left
empty. This demonstrates how it can use all the attributes and methods in its
parent class.

This is demonstrated in the parent classes file: <br>
⚫ Here John is an instance of the DevOpsStudent class, it has taken two values that are assigned into the attributes it inherited from the parent class. <br>
⚫ Secondly the parent classes method called print_details() has been called in this class even though it has not been
 created here, therefore it shows how inheritance is amazing when you want to allow classes to share attributes and methods.
```python
John = DevOpsStudent(70, "Billy bog-man")

print(John.print_details())
```