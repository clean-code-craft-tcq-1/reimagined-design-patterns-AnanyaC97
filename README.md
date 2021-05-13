# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.


### ADAPTER ###

It is a structural design pattern. It allows objects/classes with incompatible interfaces to colaborate/work together. The adapter plays the role of converter or translator. It is a bridge between two objects. This is a special object that converts the interface of one object so that another object can understand it. An adapter wraps one of the objects to hide the complexity of conversion happening behind the scenes.
###### Example ###### : 
You know a language, "A". You visit a place where language "B" is spoken. But you don't know how to speak that language. So you meet a person who knows both languages, in other words A and B. So he can act as an adapter for you to talk with the local people of that place and help you communicate with them.
###### Advantages ###### :
- Helps achieve reusability and flexibility.
- It allows two or more previously incompatible objects to interact.
###### Disadvantages ###### :
- There is a slight increase in the overhead.
- Sometimes many adaptations are required along an adapter chain to reach the type which is required.
