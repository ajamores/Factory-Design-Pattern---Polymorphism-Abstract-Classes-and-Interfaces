# Factory Design Pattern: Polymorphism, Abstract Classes, and Interfaces

This assignment is about implementing a Factory Design Pattern in Java using Polymorphism, Abstract Classes, and Interfaces. The UML class diagram shows an arrangement of classes with inheritance, association, and implementation relationships between them.

## Factory Design Pattern

The Factory Design Pattern is a creational pattern that provides an interface for creating objects. It separates the construction of objects from their implementation, allowing for flexible and decoupled code. The pattern consists of a Creator class that defines a factory method to create objects and a Product class that represents the objects being created.

## Key Concepts Learned

    - Polymorphism
    - Abstract Classes
    - Interfaces

## Implementation Details

## Polymorphism

Polymorphism is used throughout this implementation, particularly in the relationship between the TimsProduct abstract class and its concrete subclasses (Donut, Coffee, GiftCard). Since all TimsProduct objects have a getName() method, they can be treated polymorphically by any method that expects an object with a getName() method.

## Abstract Classes

The TimsProduct class is an abstract class that is used as a base for all products at Tim Horton's. This class contains a constructor and methods that are shared by all Tim Horton's products, such as getName(), getProductionCost(), and getRetailPrice(). Each subclass of TimsProduct (i.e., Donut, Coffee, GiftCard) must implement the abstract methods declared in the TimsProduct class.

## Interfaces

The Commodity interface is used to ensure that each TimsProduct object has a getProductionCost() and getRetailPrice() method. This interface is implemented by the TimsProduct class and enforced by the Java compiler. This allows other classes to use TimsProduct objects polymorphically while still being assured that they have the necessary methods to retrieve production and retail costs.

In conclusion, the Factory Design Pattern is a powerful pattern for creating flexible and reusable code. By using polymorphism, abstract classes, and interfaces, we can define common functionality for a group of related classes, and separate the construction of objects from their implementation.

## Screenshots

![image](https://i.imgur.com/JA0hOYs.png)
![image1](https://i.imgur.com/vLppNF2.png)
![image2](https://i.imgur.com/3KSd522.png)
