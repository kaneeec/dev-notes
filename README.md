> Do not take all of it literally but rather think of each item and how can you use it for the best.

# Core Design Principles
- It's impossible to get anything right for the first time, don't be afraid to rewrite it. Software is never written, it's always rewritten
- KISS: keeps you focused, only solves problems we know about, fails less, easier to understand
- YAGNI: don't write what you think might come in handy some time, you don't know it (and most like you end up with dead code)
- DRY: only one representation of a piece of knowledge for the entire product
- Forget ego and emotions when designing SW otherwise you don't focus on the problem and solution
- Always have people review your code
- When giving an advice, don't necessarily give the whole solution but only hints. Chances are that other people, using hints you gave them, can create different and better solution
- Don't make decisions immediatelly, take some time to collect more information about the problem...then you can make better decisions
- We want cohesive code have smaller pieces of well written code, couple things related, isolated unrelated
- Reduce coupling (don't interfere with previous note about cohesion)
- Single Responsibility Principle (SRP)
  - Beware long methods: hard to test, read, reuse, optimize, change, debug, lack cohesion, ...
  - Single Level Of Abstraction
  - Don't comment, refactor instead (more readable code, no obsolete comments)
  - Use compose method pattern
- Open Closed Principle (OCP)
  = open for extension, closed for modification
- Liskov's Subtitution Principle (LSP)
  - Use inheritance only for substitutability
  - If object B _should be used anywhere object A is used_, use inheritance
  - If object B _uses object A_, use composition / delegation
- Decouple using Dependency Inversion Principle
  - Class should not depend on another class but they both should depend on an abstraction
  - Use with caution, too much abstraction increases complexity

# Dangerous people
- Who don't follow instructions
- Who always follow instructions, literally

# Sources
- Core Design Principles for Software Developers (https://www.youtube.com/watch?v=llGgO74uXMI)
