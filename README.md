# Proxy Pattern

The Proxy Pattern is a structural design pattern that provides a surrogate or placeholder for another object to control access to it. It allows you to create a substitute or placeholder for another object to control access to it, which can be useful for various purposes such as managing the object's creation, controlling its access, or adding additional functionalities around the original object.

## Overview

This real-world example demonstrates the Proxy Pattern in action using a MathProxy object that serves as a surrogate for a Math object, allowing controlled access to its methods for performing basic arithmetic operations.

### Components

- **Program:** This is the entry point of the application, showcasing the usage of the MathProxy to perform arithmetic operations.
  
- **IMath:** An interface defining the basic arithmetic methods.

- **Math:** A class implementing the IMath interface, containing the actual logic for arithmetic operations.

- **MathProxy:** A proxy class that serves as an intermediary between the client code and the Math object. It controls access to the Math object's methods.

## Purpose

The purpose of the Proxy Pattern is to provide a placeholder object that can control access to another object, thereby allowing additional functionalities such as lazy initialization, access control, logging, or caching.

Feel free to explore the code to understand how the Proxy Pattern works and how it can be utilized to control access to objects efficiently.
