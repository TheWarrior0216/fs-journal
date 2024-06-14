# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > |  Let --this variable can be changed and Const/Constant can not be changed once set |

02. What is the definition of a function?

    > | A set of instructions |

03. What are the `SOLID` principles?

    > | Single Responsibility Principle (SRP)
Open/Closed Principle
Liskov’s Substitution Principle (LSP)
Interface Segregation Principle (ISP)
Dependency Inversion Principle (DIP) 

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | fruit[2] |

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | you.friends.push(them) |

06. Give an example of a JavaScript `Conditional`:

    > | if (truth == truthy){
        console.log(something here)
    } |

07. What is the main difference between `parameters` and `arguments`?

    > | A paramater is a place holder and an argument is what is inserted |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | Besides using console logs coding with someone ususally works but if by yourself I would say spell check half the time |

09. What is the difference between a `primitive` value and a `reference` value?

    > | refrences you can always come back to and add or change |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for (let i = -100; i<101; i++){
        console.log(i)
    } |
