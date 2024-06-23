# Java Classes and Objects

This repository provides a simple example to demonstrate the concepts of classes and objects in Java.

## Class and Object in Java

In Java, a **class** is a blueprint for creating objects, which are instances of that class. A class defines properties and behaviors that the objects created from the class will have. The properties are defined using fields (variables), and the behaviors are defined using methods (functions).

An **object** is an instance of a class. It contains real values instead of the blueprint.

### Example

Let's create a simple example to demonstrate a class and an object in Java.

#### Class Definition:

```java
// Define a class named 'Car'
public class Car {
    // Fields (properties) of the class
    String color;
    String model;
    int year;

    // Method (behavior) of the class
    void displayInfo() {
        System.out.println("Model: " + model);
        System.out.println("Color: " + color);
        System.out.println("Year: " + year);
    }
}
```


#### Object Definition:

```java
public class Main {
    public static void main(String[] args) {
        // Creating an object of the 'Car' class
        Car myCar = new Car();

        // Setting values to the object's fields
        myCar.color = "Red";
        myCar.model = "Toyota";
        myCar.year = 2020;

        // Calling the method to display the object's information
        myCar.displayInfo();
    }
}
