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
demonstrating the purpose of inheritance I left the child class
empty. This demonstrates how it can use all the attributes and methods in its
parent class.

