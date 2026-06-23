# Java OOP Fundamentals

A Java practice project focused on core Object-Oriented Programming concepts such as classes, objects, constructors, constructor overloading, constructor chaining, encapsulation, getter methods, setter methods, and basic validation logic.

## Overview

This project was developed as a hands-on Java fundamentals project to practice Object-Oriented Programming with simple class-based examples.

The project includes two main practice classes:

* `Person`
* `Wall`

The main focus was understanding how objects are created, how constructors work, how class fields are managed, and how simple validation logic can be implemented inside Java classes.

## Core Concepts Practiced

* Java classes and objects
* Instance variables
* Constructor creation
* Constructor overloading
* Constructor chaining
* Encapsulation
* Getter methods
* Setter methods
* Basic validation logic
* Object instantiation
* Simple method design

## Project Examples

### Person Class

The `Person` class practices basic object modeling.

Main fields include:

* `firstName`
* `lastName`
* `age`

Main methods include:

* `getFirstName()`
* `getLastName()`
* `getAge()`
* `isTeen()`

The `isTeen()` method checks whether the person's age is between 13 and 19.

### Wall Class

The `Wall` class practices encapsulation, setters, and simple validation.

Main fields include:

* `width`
* `height`

Main methods include:

* `getWidth()`
* `getHeight()`
* `setWidth()`
* `setHeight()`
* `getArea()`

The setter methods prevent negative width or height values by setting them to `0` when invalid input is provided.

## Example Usage

```java
Person person = new Person("John", "Doe", 20);

System.out.println("Firstname: " + person.getFirstName());
System.out.println("LastName: " + person.getLastName());
System.out.println("Age: " + person.getAge());
System.out.println("Is Teen: " + person.isTeen());
```

```java
Wall wall = new Wall(5, 4);

System.out.println("area= " + wall.getArea());

wall.setHeight(-1.5);

System.out.println("width= " + wall.getWidth());
System.out.println("height= " + wall.getHeight());
System.out.println("area= " + wall.getArea());
```

Expected output:

```text
area= 20.0
width= 5.0
height= 0.0
area= 0.0
```

## What I Practiced

* Creating Java classes
* Creating multiple objects from the same class
* Using constructors to initialize object state
* Applying constructor overloading
* Calling one constructor from another constructor
* Protecting fields with encapsulation
* Writing getter and setter methods
* Adding simple validation rules inside setter methods
* Writing small methods that return calculated or conditional values

## Getting Started

### Prerequisites

Make sure you have the following installed:

* Java 17+
* Maven
* IntelliJ IDEA or another Java IDE

### Installation

Clone the repository:

```bash
git clone https://github.com/emreyildirim-33/Java-OOP-Fundamentals.git
cd Java-OOP-Fundamentals
```

Run the project from your IDE or with Maven:

```bash
mvn test
```

## Notes

This project was built as a Java fundamentals training project.
The main focus was not building a full application, but practicing core OOP concepts through small, clear Java class examples.

## Repository

GitHub: https://github.com/emreyildirim-33/Java-OOP-Fundamentals
