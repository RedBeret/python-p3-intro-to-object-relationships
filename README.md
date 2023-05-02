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

Python offers a high degree of flexibility in defining classes and creating objects. With Python, we can assign attributes and methods to classes and objects, as well as add new attributes to objects even after they have been instantiated. Additionally, we can create classes that inherit attributes and methods from a parent, enabling children classes to receive those features.

However, some relationships between classes and objects are not as straightforward as parent-child relationships. For instance, the job titles "Curriculum Developer" and "Instructor" fall under the broader category of "Jobs", but they also have associated concepts such as "Duties" and "Schedules". In such cases, we can't rely solely on inheritance to solve these issues. Nevertheless, we can still use the same Python techniques that you're already familiar with to create a wide variety of relationships.

In this module, we will delve into the various types of relationships and explore how to leverage Python to establish them.
