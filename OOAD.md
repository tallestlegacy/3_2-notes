# Object Oriented Analysis & Design

###### Lecture 1

> Object Oriented Analysis by

**Object Oriented Programming** - is a _method of implementation_ in which the program is designed to be collective collections of objects. These objects are all part of a hierarchy and an instance (occurrence) of a class.

Objects are he basic building blocks of this programming paradigm.  
These classes form a hierarchy that are related through inheritance.

## Object Oriented Design

This is a method of design encompassing oo decomposition and a notation depicting both logical and physical aspects of the system under design as well as dynamic and static aspects of the system.

A system that has been decomposed has been broken down into classes or objects.

The notation will be able to show the logical (enumerate every functionality and dependency we can get from the object) and physical aspects of how we are going to arrange data components in the system.

## Object Oriented Analysis

This is a method of analysis that looks at objects and classes which are found in the vocabulary of the problem domain.

> The problem domain is where the system will be deployed

When we analyse a system, we look for the business rationale of the system design.

The object model consists of 7 elements, 4 are major elements and 3 are minor.
If a programming paradigm does not possess all four major elements, it ceases to be object oriented.

1. **Abstraction**  
   It denoted the essential characteristics of an entity while hiding the complexity behind it.

2. **Encapsulation**  
   It is the compartmentalisation of the elements of an abstraction, which serves to differentiate between the contractual interface and implementation of an abstraction.

   > An interface is all of the advertised features oof an abstraction

3. **Modularity**  
   In object orientation, modularity is a direct result of decomposition. A system that has been decomposed shows characteristics of modularity. It has been broken down into objects and classes into _modules_.  
   Modularity is therefore the breaking down of a system into objects and classes.

4. **Hierarchy**  
   It is the ranking of abstractions. When you rank ,you attach a level of seniority to these elements.

   > Ranking is the hierarchy of abstraction

5. **Typing**  
   This is the enforcement of an object to a type, so that objects of different types may not be interchanged, and can only be interchanged in a restricted way.

   ```c
   int a, b; // a and b will store integer type values
   ```

6. **Concurrency**  
   Concurrency is a property that is able to differentiate between active and inactive objects.

7. **Persistence**  
   This is when an object transcends beyond the time they were created.

###### Assignment

Software generations :

- year
- important programming concepts
- programming language

What was the topological arrangement of elements that made up software at that time  
How was data manipulated

###### Lecture 2

## Objects

An object is something that can be apprehended by the mind.  
Sometimes objects need not be tangible things but it should be tangible.

> an object is an entity that contains real attributes

It has :

- state
- identity
- behaviour

The attributes about an object defines its identity  
The behaviour about an object is how an object reacts during the time of message passing.

An object is developed/created intentionally with given functionality.  
It has to be created in a way it can collaborate with other objects.

#### Class Operations

1. **Constructor Operations** - we're initialising an object; creating space in memory for the object. It becomes a living entity.
2. **Constructor Operations** - we're initialising an object; creating space in memory for the object. It becomes a living entity.
3. **Selector** - provides a mechanism that we are able to access but not alter objects.
4. **Iterator** - it provides a means of accessing teh elements of an object in a well defined manner.
5. **Modifier** - alters the state of an object
6. **Destructor** - deallocates the memory of a given object

**Equality** - The sameness of an object  
**Assignment** - this the giving of values to the attributes about an object  
**Lifetime** - this is the time from which an object is created to the point that it is destroyed.  
**Link** - The semantic relationship between an object and another; an object requests data, and another provides it. All objects are peers in teh same hierarchical level.

An object can be :  
 **Actor** - can act upon other objects but on upon itself  
 **Server** - allows other objects to operate upon it and not on itself  
 **Agent** - capable on operating upon other objects, can be operated on, and is used to link actor and server objects

**Visibility** - before an object can create a link relationship with another object, then they other object must expose its attributes to the former.

**Aggregation Relationship** - they are whole part attributes

