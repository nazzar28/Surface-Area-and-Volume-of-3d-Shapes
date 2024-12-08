# Assignment11_OOP
3D Shapes Project Description

Project Overview

This project demonstrates the use of polymorphism in Java by designing a system to calculate the surface area and volume of various 3D shapes. The implementation includes:

An interface (Shape3DInterface) that defines the contract for 3D shapes.

Classes (Sphere, Cylinder, and Cube) that implement the interface, each providing specific implementations for the calculation methods.

A main program (Main) that generates random instances of these shapes and computes their surface area and volume.

Components

Shape3DInterface

This interface defines two methods:

surfaceArea(): Calculates and returns the surface area of the shape.

volume(): Calculates and returns the volume of the shape.

3D Shape Classes

Each shape class implements the Shape3DInterface and provides concrete implementations of the surfaceArea and volume methods.

Sphere:

Constructor accepts a radius.

Surface Area Formula: 

Volume Formula: 

Cylinder:

Constructor accepts a radius and height.

Surface Area Formula: 

Volume Formula: 

Cube:

Constructor accepts the side length.

Surface Area Formula: 

Volume Formula: 

Main Program

The Main class generates 10 random 3D shapes (instances of Sphere, Cylinder, and Cube) and stores them in a list. For each shape, the program calculates and outputs:

The type and dimensions of the shape.

Its surface area.

Its volume.

Random values for dimensions are generated within specific ranges to ensure variability in the shapes.

Use of Polymorphism

Polymorphism is a key aspect of this project. It allows the program to handle different types of shapes uniformly:

Interface Implementation: All shape classes implement the Shape3DInterface, ensuring they provide the surfaceArea and volume methods. This enforces a consistent contract across all shapes.

Dynamic Method Dispatch: In the main program, a list of Shape3DInterface references is used to store instances of Sphere, Cylinder, and Cube. When calling surfaceArea and volume on each object, the appropriate implementation (based on the object's runtime type) is executed dynamically.

This approach simplifies the management of diverse shapes, enabling the program to scale easily by adding new 3D shapes without modifying the existing codebase. The use of polymorphism ensures extensibility and adherence to object-oriented principles.



here are samples:
![Аннотация 2024-12-08 212409](https://github.com/user-attachments/assets/7238c72b-2482-4c64-8403-ee31274de792)
![Аннотация 2024-12-08 212425](https://github.com/user-attachments/assets/960563a2-f739-4a53-8f8b-c8a67ebc5bff)




