---
layout: post
title: "CppCs"
date:   2018-07-21 23:18:50 +0800
categories: Data Structure and Algorithm
tags: 微小的代码工作
description: Data Structure
---
**What is Data Structure**
In computer science, a data structure is a data organization and storage format that enables efficient access and modification.More precisely, a data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data.
</br>
**Usage**
</br>
Data structures can implement one or more particular abstract data types (ADT), which specify the operations that can be performed on a data structure and the computational complexity of those operations. In comparison, a data structure is a concrete implementation of the space provided by an ADT.

Different kinds of data structures are suited to different kinds of applications, and some are highly specialized to specific tasks. For example, relational databases commonly use B-tree indexes for data retrieval, while compiler implementations usually use hash tables to look up identifiers.

Data structures provide a means to manage large amounts of data efficiently for uses such as large databases and internet indexing services. Usually, efficient data structures are key to designing efficient algorithms. Some formal design methods and programming languages emphasize data structures, rather than algorithms, as the key organizing factor in software design. Data structures can be used to organize the storage and retrieval of information stored in both main memory and secondary memory.
</br>
**Implementation**
</br>
Data structures are generally based on the ability of a computer to fetch and store data at any place in its memory, specified by a pointer—a bit string, representing a memory address, that can be itself stored in memory and manipulated by the program. Thus, the array and record data structures are based on computing the addresses of data items with arithmetic operations; while the linked data structures are based on storing addresses of data items within the structure itself. Many data structures use both principles, sometimes combined in non-trivial ways (as in XOR linking).

The implementation of a data structure usually requires writing a set of procedures that create and manipulate instances of that structure. The efficiency of a data structure cannot be analyzed separately from those operations. This observation motivates the theoretical concept of an abstract data type, a data structure that is defined indirectly by the operations that may be performed on it, and the mathematical properties of those operations (including their space and time cost).
</br>
**Examples**
</br>
Main article: [List of data structures](https://en.wikipedia.org/wiki/List_of_data_structures)

There are numerous types of data structures, generally built upon simpler primitive data types:[8]

    An array is a number of elements in a specific order, typically all of the same type. Elements are accessed using an integer index to specify which element is required (Depending on the language, individual elements may either all be forced to be the same type, or may be of almost any type). Typical implementations allocate contiguous memory words for the elements of arrays (but this is not always a necessity). Arrays may be fixed-length or resizable.
    A linked list (also just called list) is a linear collection of data elements of any type, called nodes, where each node has itself a value, and points to the next node in the linked list. The principal advantage of a linked list over an array, is that values can always be efficiently inserted and removed without relocating the rest of the list. Certain other operations, such as random access to a certain element, are however slower on lists than on arrays.
    A record (also called tuple or struct) is an aggregate data structure. A record is a value that contains other values, typically in fixed number and sequence and typically indexed by names. The elements of records are usually called fields or members.
    A union is a data structure that specifies which of a number of permitted primitive types may be stored in its instances, e.g. float or long integer. Contrast with a record, which could be defined to contain a float and an integer; whereas in a union, there is only one value at a time. Enough space is allocated to contain the widest member datatype.
    A tagged union (also called variant, variant record, discriminated union, or disjoint union) contains an additional field indicating its current type, for enhanced type safety.
    A class is a data structure that contains data fields, like a record, as well as various methods which operate on the contents of the record. In the context of object-oriented programming, records are known as plain old data structures to distinguish them from classes.

In addition, graphs and binary trees are other commonly used data structures. 
