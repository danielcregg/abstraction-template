# Abstraction

Gitpod URL prefix: https://gitpod.io/#

In Object-oriented programming, abstraction is a process of hiding the implementation details from the user, only the functionality will be provided to the user. In other words, the user will have the information on what the object does instead of how it does it. 

Abstraction is the quality of dealing with ideas rather than events. For example, when you consider the case of e-mail, complex details such as what happens as soon as you send an e-mail, the protocol your e-mail server uses are hidden from the user. Therefore, to send an e-mail you just need to type the content, mention the address of the receiver, and click send. 

1. Create an abstract class called AbstractClass 
2. Add an instance variable called age 
3. Add a constructor with one input parameter that sets age 
4. Write a getter and setter for the age variable
5. Add an abstract method called returnPi()
6. Create a regular non-abstract class (i.e. a concrete class) called AbstractClassDriver
7. Try to instantiate an object of type AbstractClass inside AbstractClassDriver. What happened?
8. Create a regular non-abstract class (i.e. a concrete class) called AbstractSubClass that extents AbstractClass 
9. Add a constructor that sets the age variable in the super class.
10. Implement the returnPi() method. It will return 3.14 to the console. 
11. Create a driver class called AbstractClassDriver that calls the methods inside AbstractSubClass.

# Employee 
1. Create an abstract class called Employee 
2. Every employee will have a name, address, age and salary. Create variables for these. 
3. Create a constructor that sets the instance varibales above. 
4. Add an abstract method called computePay() 
5. Create an Engineer class that extends the Employee class 
6. Implement the computePay() method. This method will return the salary / 12. 
7. Create a Manager class that extends the Employee class 
8. Give the Manager class a bonus variable 
9. Implement the abstract method compute pay method for the Manager. This method will return the salary plus the bonus /12.  
10. Create driver class and run methods. 
