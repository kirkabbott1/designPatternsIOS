# App Architectures

## MVC, MVP, MVVM, Coordinator, VIPER

https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52


## Flux

http://blog.benjamin-encz.de/post/real-world-flux-ios/#:~:text=Flux%20is%20a%20very%20lightweight,for%20client%2Dside%20web%20applications.&text=In%20the%20Flux%20architecture%20a,that%20subscribed%20to%20the%20store.


## Homework

Write a small excerpt on each of the above architectural patterns and discuss how they are different.
Give a list of reasons why to use one over the other.


# Design Patterns

https://medium.com/@suresh.kansujiya/gang-of-four-swift-ios-9eda6bd3e264

https://medium.com/cocoaacademymag/real-world-ios-design-patterns-3e5aad172094

## Creational 

### Abstract Factory
    -The abstract factory pattern is used to provide a client with a set of related or dependant objects. 
    -The "family" of objects created by the factory are determined at run-time.
### Factory Method
    -The factory pattern is used to replace class constructors, abstracting the process of object generation so that the type of the object instantiated can be determined at run-time.
### Builder
    -The builder pattern is used to create complex objects with constituent parts that must be created in the same order or using a specific algorithm. 
    -An external class controls the construction algorithm.
### Singleton
    -Ensures only one instance of an object is created.

### Prototype
    -Creates a new object from an existing object.


## Structural 

### Adapter
    -Allows for two incompatible classes to work together by wrapping an interface around one of the existing classes.
### Decorator
    -Allows for an object’s behavior to be extended dynamically at run time.
### Facade
    -Provides a simple interface to a more complex underlying object.
### Proxy
    -Provides a placeholder interface to an underlying object to control access, reduce cost, or reduce complexity.
    
### Bridge
    -Decouples an abstraction so two classes can vary independently.
### Composite
    -Takes a group of objects into a single object.
### Flyweight
    -Reduces the cost of complex object models.


## Behavorial

### Chain of Responsibility
    -Delegates commands to a chain of processing objects.
### Command
    -Creates objects which encapsulate actions and parameters.
### Interpreter
    -Implements a specialized language.
### Iterator
    -Accesses the elements of an object sequentially without exposing its underlying representation.
### Mediator
    -Allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
### Memento
    -Provides the ability to restore an object to its previous state.
### Observer
    -Is a publish/subscribe pattern which allows a number of observer objects to see an event.
### State
    -Allows an object to alter its behavior when its internal state changes.
### Strategy
    -Allows one of a family of algorithms to be selected on-the-fly at run-time.
### Template Method
    -Defines the skeleton of an algorithm as an abstract class, allowing its sub-classes to provide concrete behavior.
### Visitor
    -Separates an algorithm from an object structure by moving the hierarchy of methods into one object.


## Homework

Write a small paragraph about different design patterns. (1 paragraph per) Particularly Singleton, Factory, Facade, Decorator, Adapter, and two others of your choice. Explain what they are and why/when they should be used.
