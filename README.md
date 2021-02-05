# Javascript  
Javascript Documentation :memo: 


<img src= "https://www.tecschool.net/wp-content/uploads/2019/11/funciones-en-javascript-t1.png" width="400" height="200">

Javascript _enhances_ our Web page.
It is used to add interactive features.

- JavaScript is an Object Oriented Programming (OOP) language.

- JavaScript statements are placed within the <script>... </script> HTML tags in a web page.
  - ```javascript
        <script>
           javascript code
        </script>
    ```

 

### Variable in Javascript

Two keywords **let** and **const** are used to declare variable in javascript.

Example: ``` let name = "divya" ```
         ``` const value = 5 ```
       
Earlier the keyword **var** was used.
  
 - [Why don’t we use var anymore?] (https://blog.usejournal.com/awesome-javascript-no-more-var-working-title-999428999994)
 


### Difference between let and const

With **const**, you can not re-assign a value to the variable. With **let**, you can.


### Type conversion

The three most widely used type conversions are to string, to number, and to boolean.

You can use the typeof operator to find the data type of a JavaScript variable.

- String Conversion

```javascript 
let value = true;
console.log(typeof value); // boolean

value = String(value); // now value is a string "true"
console.log(typeof value); // string
```

- Numeric Conversion

```javascript 
let str = "123";
console.log(typeof str); // string

let num = Number(str); // becomes a number 123
console.log(typeof num); // number
```

- Boolean Conversion

```javascript 
console.log( Boolean(1) ); // true
console.log( Boolean(0) ); // false

console.log( Boolean("hello") ); // true
console.log( Boolean("") ); // false
```


### Data Types in Javascript

Data type | Example
----------| --------------
String    | ``` let name = "divya" ```
Number    |  ``` let n = 5 ```
Boolean   |  ```true or false```
Array     | ``` let cars = ["Volvo", "Audi", "BMW"] ```
Object    | ``` let person = {firstName: "divya", lastName: "Sahajwani"} ```
Undefined | ``` let car; ```  A variable without a value
Null      | value which represents “nothing”, “empty” or “value unknown”



### Operators in Javascript 

- **Arithmetic Operators** are used to perform arithmetic on numbers
  - +,-,*,**,/,%,++,--
- **Assignment Operators** assign values to JavaScript variables
  - =,+=,-=,*=,/=,%=,**=
- **Comparison Operators** compares to values.
  - ==,===,!=,!==,>,<,>=,<=,?
- **Logical Operators**  is a function that denotes a logical operation.
  - &&(logical and),||(logical or),!(logical not)
- **Bitwise Operators** is an operator used to perform bitwise operations on bit patterns or binary numerals
   - &(AND),|(OR),~(NOT),^(XOR),<<(zero fill left shift),>>(signed right shift),>>>(zero fill right shift)
   
   
### Function

A function is a reusable set of statements to perform a task or calculate a value. Functions can be passed one or more values and can return a value at the end of their execution.

```javascript
// Defining the function:
function sum(num1, num2) {
  return num1 + num2;
}
 
// Calling the function:
sum(3, 6); // 9
```

### Loops

- _While Loop_ - The while loop creates a loop that is executed as long as a specified condition evaluates to true. The loop will continue to run until the condition evaluates to false. 

```javascript
while (condition) {
  // code block to be executed
}
 
let i = 0;
 
while (i < 5) {        
  console.log(i);
  i++;
}
```

- _Do While_- A do...while statement creates a loop that executes a block of code once, checks if a condition is true, and then repeats the loop as long as the condition is true.

```javascript
x = 0
i = 0
 
do {
  x = x + i;
  console.log(x)
  i++;
} while (i < 5);
 
// Prints: 0 1 3 6 10
```

- _For Loop_  - A for loop declares looping instructions, with an initialization,stopping condition,iteration statement.

```javascript
for (let i = 0; i < 4; i += 1) {
  console.log(i);
};
 
// Output: 0, 1, 2, 3
```



