# HierarchicalInheritanceExample
Hierarchical Inheritance Example in Java
📋 Overview
This project demonstrates Hierarchical Inheritance in Java, where multiple child classes (Child2 and Child3) inherit from a common parent class (Parent2).

It showcases:

How child classes inherit properties and methods from a parent class.

How each child class can also have its own unique properties and methods.

📂 Project Structure
Parent2 class:

Property: familyCar (String)

Method: greet() (Prints a greeting message)

Child2 class (extends Parent2):

Property: hobby (String)

Method: child2method() (Prints a message related to Child2)

Child3 class (extends Parent2):

Property: favoriteSport (String)

Method: child3Method() (Prints a message related to Child3)

HierarchicalInheritanceExample class:

Contains the main() method.

Creates instances of Child2 and Child3.

Demonstrates accessing both inherited and child-specific properties and methods.

🚀 How It Works
Child2 and Child3 objects have access to:

Their own fields and methods

Inherited fields (familyCar) and methods (greet()) from Parent2

Output is printed to the console showing:

Unique features of each child class

Shared features inherited from the parent class

🛠 Example Output
pgsql
Copy
Edit
Hobby: Painting
This is child2
Family car: Toyota
Hello from Parent
Favorite sport: Soccer
This is child3
Family car: Toyota
Hello from Parent
📚 Concepts Demonstrated
Inheritance (Hierarchical Inheritance)

Method Inheritance

Object-Oriented Programming (OOP) Basics
