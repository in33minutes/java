---
layout: default
title: Immutable Class
parent: Basics
nav_order: 2
permalink: /docs/basics/immutable-class
---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

### What is an immutable class in Java?

Immutable objects are instances whose state doesn’t change after it has been initialized. For example, String is an immutable class and once instantiated its value never changes.

### Benefits of Immutable Class in Java

1. Caching
2. Thread safe

### How to make a class immutable?

To create an immutable class in Java, you have to do the following steps.

1. Declare the class as final so it can’t be extended.
2. Make all fields private so that direct access is not allowed.
3. Don’t provide setter methods for variables.
4. Make all mutable fields final so that its value can be assigned only once.
5. Initialize all the fields via a constructor performing deep copy.
6. Perform cloning of objects in the getter methods to return a copy rather than returning the actual object reference.

### Shallow copy vs Deep copy

### Why Deep Copy is important for immutability?
