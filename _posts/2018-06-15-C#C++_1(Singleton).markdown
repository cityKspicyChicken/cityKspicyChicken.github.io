---
layout: post
title: "Singletion pattern"
date:   2018-02-15 23:18:50 +0800
categories: C++/C#
tags: 微小的代码工作
description: C++ you are the world, C# you are the children
---
Singletion pattern

In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one object. This is useful when exactly one object is needed to coordinate actions across the system. The concept is sometimes generalized to systems that operate more efficiently when only one object exists, or that restrict the instantiation to a certain number of objects. The term comes from the mathematical concept of a singleton.<br/>
**Overview**<br/>
The singleton design pattern is one of the twenty-three well-known "Gang of Four" design patterns that describe how to solve recurring design problems to design flexible and reusable object-oriented software, that is, objects that are easier to implement, change, test, and reuse.

The singleton design pattern solves problems like:

    How can it be ensured that a class has only one instance?
    How can the sole instance of a class be accessed easily?
    How can a class control its instantiation?
    How can the number of instances of a class be restricted?

The singleton design pattern describes how to solve such problems:

    Hide the constructor of the class.
    Define a public static operation (getInstance()) that returns the sole instance of the class.

The key idea in this pattern is to make the class itself responsible for controlling its instantiation (that it is instantiated only once).
The hidden constructor (declared private) ensures that the class can never be instantiated from outside the class.
The public static operation can be accessed easily by using the class name and operation name (Singleton.getInstance()).


see more by visiting[Singleton](https://en.wikipedia.org/wiki/Singleton_pattern "Singleton")
