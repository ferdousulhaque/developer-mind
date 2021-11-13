# Developer Mind

Developer mind is a respository for developers or software engineer or software architect, while developing a software or application, should keep in mind.

# Mind Map

1.  **DRY - Don't Repeat Yourself.**
    - Is a principle of software development aimed at reducing repetition of software patterns, replacing it with abstractions or using data normalization to avoid redundancy.

2. **YAGNI - You aren't gonna need it**
    - Is a principle of extreme programming (XP) that states a programmer should not add functionality until deemed necessary. *Example premature abstraction is not good.*
    
3. **KISS - Keep It Simple Silly**
    - May add extra code for readability, it is good.

4. **Composition over Inheritance**
    - Composition over inheritance (or composite reuse principle) in object-oriented programming (OOP) is the principle that classes should achieve polymorphic behavior and code reuse by their composition (by containing instances of other classes that implement the desired functionality) rather than inheritance from a base or parent class.

    - Because, multi-level inheritance makes code harder to understand, debug and test.

5. **Interface over implementation**
    - The process of defining an `Interface` is `Abstraction`
    - From SOLID Principles, `D` stands for `Dependency inversion principle` means high-level modules should not depend on the low-level modules, instead should depend on abstractions not on concretions.
    - As example, instead of passing a exact class as dependency, pass an interface that the dependency conforms to.

    ```php
    public function __construct(private ShippingInterface $shippingInterface){
        // Code
    } 
    ```

6. **Entity and Value Object from Domain Driven Design**
    - [*Read Link 1*](https://blog.jannikwempe.com/domain-driven-design-entities-value-objects)

7. **Strategy Design Pattern**
    - A class behavior or its algorithm can be changed at run time. This type of design pattern comes under behavior pattern.
    - [*Read Link 1*](https://www.tutorialspoint.com/design_pattern/strategy_pattern.htm)
    - [*Read Link 2*](https://en.wikipedia.org/wiki/Strategy_pattern)

8. **Don't use double or float to represent currency, use strings instead**
    - [*IEEE-754*](https://en.wikipedia.org/wiki/IEEE_754)

9. **In PHP, Avoid using associative array if not necessary, use Object.**
    - PHP associative array is a hashmap and it requires more memory if you are dealing with large array of data and memory is crucial, avoid using it.
    - [*Read Link 1*](https://www.php.net/manual/en/language.types.array.php)
    - [*Read Link 2*](https://medium.com/7shifts-engineering-blog/php-arrays-arent-really-arrays-57b627a1e46a)

10. **Abstraction class instead of interface**
    - [*Read Link 1*](https://betterprogramming.pub/choosing-between-interface-and-abstract-class-7a078551b914)

### Good Reading Document
- Clean Code PHP with Example (https://github.com/jupeter/clean-code-php)

# Contribution

There can be a lot of other ways to improve the code quality by keeping in mind. I am requesting to add more to the list and we can use this repo as a Mind mapper for the developers.

## How to contribute

Please help to follow the steps as below:

```
1. Fork the repository to your own repo.
2. Clone the repo to your own workstation.
3. Create a new branch, any name your choice
4. Add the required mind mapper to the list or add example codebase etc. Please do follow the same pattern.
5. Add, Commit and push the changes to the repository
6. Create a pull request to this repo.
```

Thank you for your contribution to the open source.

# Thank you for reading