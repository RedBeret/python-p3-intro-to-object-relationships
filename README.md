# Intro to Object Relationships

## Learning Goals

- Build relationships between objects and classes.
- Practice strategies for one-to-one, one-to-many, and many-to-many relationships.

***

## Key Vocab

- **Domain**: a visualization of a set of relationships used to solve a problem.
  A Python domain will show all of the classes involved in an application and
  how they relate to one another.
- **One-to-Many**: a type of relationship between objects where one object in
  class A is connected to multiple objects in class B. **e.g.** One dog
  organizing their toys.
- **Many-to-Many**: a type of relationship between objects where multiple
  objects in table A are connected to multiple objects in table B. **e.g.**
  Students have many instructors and instructors have many students.

***

## Introduction

Python provides us a great deal of flexibility when defining classes and
creating objects. We can give attributes and methods to classes and their
objects, even adding brand new attributes to those objects after they are
instantiated. We can also create classes that _inherit_ from one another, with
different children getting the same attributes and methods from a parent.

Some relationships between classes and objects aren't quite as simple as
parent-to-child. "Curriculum Developer" and "Instructor" are clearly examples
of "Jobs", but how do they relate to important related concepts like "Duties"
and "Schedules"? We can't use inheritance to solve these problems, but we can
use Python techniques that you're already familiar with to build all variety
of relationships.

In this module, we will explore these different types of relationships and how
to use Python to create them.
