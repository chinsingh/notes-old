# Interface and Abstract Class

> Abstract class achieves partial abstraction (0 to 100%) and interface achieves full abstraction (100%)

|   |                                        | Abstract Class                                            | Interface                                                                               |
|---|----------------------------------------|-----------------------------------------------------------|-----------------------------------------------------------------------------------------|
| 🟢 | Types of Methods                       | can have abstract and non-abstract methods                | can have only abstract methods. After java 8, can have default and static methods also. |
| 🟢 | [[Multiple Inheritance]] Support           | Doesn't support multiple inheritance                      | Supports multiple inheritance                                                           |
| 🟢 | Types of variables                     | Can have final, non-final, static, non-static variables   | Only static final variables                                                             |
|   | Implementation of each other           | Can provide the implementation of interface               | Can't provide implementation of abstract class                                          |
|   | Keywords                               | - abstract keyword - extends keyword                      | - interface keyword - implements keyword                                                |
|   | Extending other classes and interface  | can extend another class and implement multiple interface | can extend only other interfaces                                                        |
| 🟢 | Access level of members                | class members can be private and protected also           | members are public by default                                                           |

- [[When to use interface and when to use abstract class]]
- [[How do interface and abstract class achieve abstraction]]
- Static methods cannot be abstract as they cannot be overriden.