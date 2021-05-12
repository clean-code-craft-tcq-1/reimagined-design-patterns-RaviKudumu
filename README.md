# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.

# Adapter
  ## Principle:
    Adapter design pattern work on the principle of using multiple utility interfaces inside the main interface
  ## Problems:
    Problems where already implemented interface functionalities can be used like email sending, file conversions
  ## Uses:
    We can reuse existing solution and complete application fast
    Less repetion
# Builder
  ## Principle:
    This pattern does not allow usage of internal functionality flexibly but flexible to create complete functionality.
  ## Problems:
    When we have dependency on output rather solution implemented
  ## Uses:
    We can follow independent approach towards building the solution
    Have complete controll over the functionality
# Decorator
  ## Principle:
    This pattern allows to modify few dynamically functionalities at runtime and have no controll over complete functionality
  ## Problems:
    Responsibilities should be added to (and removed from) an object dynamically at run-time.
    A flexible alternative to subclassing for extending functionality should be provided.
  ## Uses:
    A decorator makes it possible to add or alter behavior of an interface at run-time
# Composite
  ## Principle:
    This pattern handles when child objects are similar to main object(hierarchy handling)
  ## Problems:
    When we have group inside other gourp. Ex: Cost Center group can under other group(AA->XX->ZZ-><Cost Center>)
  ## Uses:
    Composite should be used when clients ignore the difference between compositions of objects and individual objects
    When multiple objects have similar code
    

