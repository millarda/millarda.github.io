---
layout: essay
type: essay
title: Design Patterns: Finding Solutions
# All dates must be YYYY-MM-DD format!
date: 2019-04-27
labels:
  - Learning
  - Etiquette
---
<h2>Quick Background of Design Patterns</h2>
Design patterns are a useful tool for figuring out a problem. It provides a general process or idea to solve problems that could exist in a software environment. They can also be represented as a concept that one might use when deciding how to design part of a project.
<img class="ui image" src="{{ site.baseurl }}/images/so-logo.png">

<h2>Examples of Design Patterns</h2>
I will cover three types of design patterns: Creational, Structural and Behavioral.

<h3>Creational</h3>
 Creational desgin patterns are based on how one would design the classes and objects with respect to each other in a project. For example, a "Singleton" is the design pattern where a class will only exist as a single instance. This could be something like a world in a game environment or a network of a nodes. Another one is the "Prototype" is an object that has a general description of itself. It allows the developer to easily copy or alter the prototype to create new similar objects that fit their design. Another one would 
 
<h3>Structural</h3>
Structural Design patterns act as a format for the composition of an object or class. The "Decorator" design pattern is the idea of adding all optional parts of a class as a single decorator class. This is alternative to creating separate classes for each option that one would have available for the original object. This neatly organizes the code so that when it is in use there is a straightforward way to check off different options in a compatible manner. Similarly, the "Facade" design pattern is for wrapping multiple related classes under a single high level interface. This is so that people can easily use the code without learning every intricate detail or having to search through all the different classes to find the one that they need.

<h3>Behavioral</h3>
Behavioral design patterns are a way to implement communication betwen objects. One example is the "Chain of Responsibility" design pattern which essentially asks a number of different processes to complete a task. The first process will look an either begin work on the task or pass it on to the next process. A good example of this is a program for dispensing change. If it needs to dispense twenty cents it might first ask the quarter process to work on it which then passes on the responsibility to the dime process. The dime process takes a piece of the work away by removing 10 cents from the task. In this case the task is incomplete and sent back to the chain, where the dime process would operate again. Another example would the "Mediator" design pattern which essentially has an object act a layer of communication between other objects. This is useful for when you have an unknown amount of objects at any given time and they need information from each other. A common use of the mediator object is to enforce rules so that other objects don't step on each other's toes. An example of this would be a read/write mediator which ensures that a reading process doesn't occur during the same time as writing process.

<h2>My Experience with Design Patterns</h2>
I have used many design patterns in my engineering academic career. I didn't really know that they were classified as design patterns as I used them. The first step to figuring out how to do something is to decide the structure or layout. For me, this would be deciding which design pattern to use. For example I use the "Singleton" design pattern in my news article grouping program that requires a class for completing different steps of the process. Most of these classes are created only once, but they exist separetly for the purpose of organization and effectiveness. It is also possible that later on I will need to begin using a singleton class multiple times in the same instance. Another reason for this design is that I could bring a class over to another project without draggining along unncessary code. An example of "Decorator" in my work could be this website which uses a config file that lets me select which visual designs and backend versions I would like to use. For example I could request to use a different theme for this website or the name of my bio page.
