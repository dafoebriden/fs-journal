# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > |var, let, const|

02. What is the definition of a function?

    > | a function is a mini program made to perform a specific task|

03. What are the `SOLID` principles?

    > |single, open, liskov, interference, dependency |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > |fruit.splice[2,1]|

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

    > |you.push.friends(them)
    them.push.friends(you)|

06. Give an example of a JavaScript `Conditional`:

    > |function printWholeNumbers(number){
    if(number == Math.round(number)){
        console.log(number)
    }
    }|
07. What is the main difference between `parameters` and `arguments`?

    > |parameters filter the content through itself so you only get the objects with that/those specific parameters
    while arguments the data you pass through the parameters|

08. Instead of writing everything to the console, what is a better way to debug your code?

    > |to console log in your javascript and to use breakpoints|

09. What is the difference between a `primitive` value and a `reference` value?

    > |a primitive value is a value that can change and is used as a base/starting value. a reference value is a constant value that does not change over time.|

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > |function numbersLoop()
    for (let i = -100, i =< 100 i++)
    console.log(i) |
