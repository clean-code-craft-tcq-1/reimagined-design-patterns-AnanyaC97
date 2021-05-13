# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.


### ADAPTER

It is a structural design pattern. It allows objects/classes with incompatible interfaces to colaborate/work together. The adapter plays the role of converter or translator. It is a bridge between two objects. This is a special object that converts the interface of one object so that another object can understand it. An adapter wraps one of the objects to hide the complexity of conversion happening behind the scenes.
###### Example : 
You know a language, "A". You visit a place where language "B" is spoken. But you don't know how to speak that language. So you meet a person who knows both languages, in other words A and B. So he can act as an adapter for you to talk with the local people of that place and help you communicate with them.
###### Advantages :
- Helps achieve reusability and flexibility.
- It allows two or more previously incompatible objects to interact.
###### Disadvantages :
- There is a slight increase in the overhead.
- Sometimes many adaptations are required along an adapter chain to reach the type which is required.


### PROXY

It is a structural design pattern that lets you provide a substitute or placeholder for another object that servers the functionality. Simply, proxy means an object representing another object. It provides the control for accessing the original object. It controls and manages access to the object they are protecting.
###### Example : 
A cheque or credit card is a proxy for what is in our bank account. It can be used in place of cash, and provides a means of accessing that cash when required. Both implement the same interface: they can be used for making a payment. A consumer feels great because there’s no need to carry loads of cash around. A shop owner is also happy since the income from a transaction gets added electronically to the shop’s bank account without the risk of losing the deposit or getting robbed on the way to the bank.
###### Advantages :
- You can introduce new proxies without changing the service or clients.
- It avoids duplication of objects which might be huge size and memory intensive.
- One of the advantages of Proxy pattern is security. It provides the protection to the original object from the outside world.
###### Disadvantages :
- The code may become more complicated since you need to introduce a lot of new classes.
- The response from the service might get delayed.


### OBSERVER

It is a behavioral design pattern. It is like a subscription mechanism to notify multiple objects about any events that happen to the object they’re observing. The Observer Pattern defines a one to many dependency between objects so that one object changes state, all of its dependents are notified and updated automatically. It is used when the change of a state in one object must be reflected in another object
###### Example :
Social media, RSS feeds, email subscription in which you have the option to follow or subscribe and you receive latest notification.
###### Advantages :
- It provides the support for broadcast-type communication
- A loosely coupled design between objects that interact, which means that the interacting objects should have less information about each other.
###### Disadvantages :
- Subscribers are notified in random order.
- It will be the cause of large complexity code if not implemented properly.


### STATE

It is a behavioral design pattern. It lets an object alter its behavior when its internal state changes. The behavior gets changed at runtime depending on the state. It is used when the operations have large, multipart conditional statements that depend on the state of an object.
###### Example :
ATM machine, you can not perform any transaction until you swipe the card, and change the machine state to card swiped.
###### Advantages :
- Simplify the code by eliminating bulky state machine conditional statements, minimize conditional complexity.
- Introduce new states without changing existing state classes or the context.
###### Disadvantages :
- If a state machine has only a few states or rarely changes, it makes it unnecessary.
