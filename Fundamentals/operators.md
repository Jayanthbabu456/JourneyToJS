## JavaScript Operators

JavaScript operators are `symbols` or `special characters` that allow you to perform operations on data, such as `variables`, `values`, or `expressions`. They help you manipulate data, perform `calculations`, `compare values`, and make `decisions` in your code. Operators are fundamental building blocks in JavaScript programming and are used to create complex logic and algorithms.

### There are various operators supported by JavaScript.

- JS Arithmetic Operators
- JS Assignment Operators
- JS Comparison Operators
- JS Logical Operators
- JS Bitwise Operators
- JS Ternary Operators
- JS typeof Operator

1. JavaScript Arithmetic Operators:

   Used to perform basic arithmetic operations on numerical values.

   | Operator | Name                        | Example        |
   | -------- | --------------------------- | -------------- |
   | `+`      | Addition                    | `x + y`        |
   | `-`      | Subtraction                 | `x - y`        |
   | `*`      | Multiplication              | `x * y`        |
   | `/`      | Division                    | `x / y`        |
   | `%`      | Reminder                    | `x % y`        |
   | `++`     | Increment (increments by 1) | `++x` or `x++` |
   | `--`     | Decrement (decrements by 1) | `--x` or `x--` |
   | `**`     | Exponentiation (Power)      | `x ** y`       |
   | `+a`     | Unary                       | `+x`           |
   | `-a`     | Negation                    | `-x`           |

   - Examples:

     ```javascript
     let a = 5;
     let b = 2;

     // Addition
     let sum = a + b;
     console.log(sum); // Output: 7

     // Subtraction
     let difference = a - b;
     console.log(difference); // Output: 3

     // Multiplication
     let product = a * b;
     console.log(product); // Output: 10

     // Division
     let quotient = a / b;
     console.log(quotient); // Output: 2.5

     // Modulus (remainder)
     let remainder = a % b;
     console.log(remainder); // Output: 1

     // Exponentiation
     let exponent = a ** b;
     console.log(exponent); // Output: 25 (5^2)

     //Increment
     let increment = ++a;
     console.log(increment); // Output: 6

     //Decrement
     let decrement = --b;
     console.log(decrement); // Output: 1

     //Unary
     let unary = +a;
     console.log(unary); // Output: 5

     //Negation
     let negation = -a;
     console.log(negation); // Output: -5
     ```

2. JavaScript Assignment Operators:

   Used to assign values to variables.

   | Operator | Name                      | Example                    |
   | -------- | ------------------------- | -------------------------- |
   | `=`      | Assugnment operator       | `Y = 7`                    |
   | `+=`     | Addition assignment       | `Y += 1 gives Y = Y + 1`   |
   | `-=`     | Subtraction assignment    | `Y -= 1 gives Y = Y - 1`   |
   | `*=`     | Multiplication assignment | `Y *= 1 gives Y = Y * 1`   |
   | `/=`     | Division assignment       | `Y /= 1 gives Y = Y / 1`   |
   | `%=`     | Remainder assignment      | `Y %= 1 gives Y = Y % 1`   |
   | `**=`    | Exponentiation Assignment | `Y **= 1 gives Y = Y ** 1` |

   - Examples:

     ```javascript
     let num = 10;

     // Addition assignment
     num += 5; // Equivalent to: num = num + 5;
     console.log(num); // Output: 15

     // Subtraction assignment
     num -= 3; // Equivalent to: num = num - 3;
     console.log(num); // Output: 7

     // Multiplication assignment
     num *= 2; // Equivalent to: num = num * 2;
     console.log(num); // Output: 20

     // Division assignment
     num /= 4; // Equivalent to: num = num / 4;
     console.log(num); // Output: 2.5

     // Remainder  assignment
     num %= 4; // Equivalent to: num = num % 4;
     console.log(num); // Output: 2

     // Exponentiation  assignment
     num **= 4; // Equivalent to: num = num ** 4;
     console.log(num); // Output: 10000
     ```

3. JavaScript Comparison Operators:

   Used to compare values and return boolean results (true or false).

   | Operator | Description                                                                                      | Example   |
   | -------- | ------------------------------------------------------------------------------------------------ | --------- |
   | `==`     | `Equal to` : returns true if the operands are equal                                              | `x == y`  |
   | `!=`     | `Not equal to` : returns true if the operands are not equal                                      | `x != y`  |
   | `===`    | `Strict equal to` : true if the operands are equal and of the same type                          | `x === y` |
   | `!==`    | `Strict not equal to` : true if the operands are equal but of different type or not equal at all | `x !== y` |
   | `>`      | `Greater than` : true if left operand is greater than the right operand                          | `x > y`   |
   | `>=`     | `Greater than or equal to` : true if left operand is greater than or equal to the right operand  | `x >= y`  |
   | `<`      | `Less than` : true if the left operand is less than the right operand                            | `x < y`   |
   | `<=`     | `Less than or equal to` : true if the left operand is less than or equal to the right operand    | `x <= y`  |

   - Examples:

     ```javascript
     let x = 10;
     let y = 5;

     console.log(x > y); // Output: true
     console.log(x < y); // Output: false
     console.log(x >= y); // Output: true
     console.log(x <= y); // Output: false
     console.log(x == y); // Output: false
     console.log(x === y); // Output: false
     console.log(x != y); // Output: true
     console.log(x !== y); // Output: true
     ```

4. JavaScript Logical Operators:

   Used to perform logical operations and return boolean results.

   | Operator | Description                                                                            | Example  |
   | -------- | -------------------------------------------------------------------------------------- | -------- |
   | `&&`     | `Logical AND` : true if both the operands are true, else returns false                 | `x && y` |
   | `ll`     | `Logical OR` : true if either of the operands is true; returns false if both are false | `x ll y` |
   | `!`      | `Logical NOT` : true if the operand is false and vice-versa.                           | `!x`     |

   - Examples:

     ```javascript
     let p = true;
     let q = false;

     console.log(p && q); // Output: false (Logical AND)
     console.log(p || q); // Output: true (Logical OR)
     console.log(!p); // Output: false (Logical NOT)
     ```

5. JavaScript Bitwise Operators:

   Used to perform bitwise operations on integer values.

   | Operators | Name                         | Example   |
   | --------- | ---------------------------- | --------- |
   | `&`       | Bitwise AND                  | `x & y`   |
   | `l`       | Bitwise OR                   | `x l y`   |
   | `^`       | Bitwise XOR                  | `x ^ y`   |
   | `~`       | Bitwise NOT                  | `~x`      |
   | `<<`      | Left shift                   | `x << y`  |
   | `>>`      | Sign-propagating right shift | `x >> y`  |
   | `>>>`     | Zero-fill right shift        | `x >>> y` |

   - Examples:

     ```javascript
     let a = 5; // Binary: 0101
     let b = 3; // Binary: 0011

     console.log(a & b); // Output: 1 (Bitwise AND: 0101 & 0011 = 0001)
     console.log(a | b); // Output: 7 (Bitwise OR: 0101 | 0011 = 0111)
     console.log(a ^ b); // Output: 6 (Bitwise XOR: 0101 ^ 0011 = 0110)
     console.log(~a); // Output: -6 (Bitwise NOT: ~0101 = -(0110 + 1) = -0111 = -6)
     console.log(a << 1); // Output: 10 (Left shift: 0101 << 1 = 1010)
     console.log(b >> 1); // Output: 1 (Right shift: 0011 >> 1 = 0001)
     console.log(b >>> 1); // Output: 1 (Right shift: 0011 >> 1 = 0001)
     ```

6. JavaScript Ternary Operator:

   - Definition: A shorthand conditional operator that evaluates an expression and returns one of two values based on a condition.
   - Example:
     ```javascript
     let age = 20;
     let status = age >= 18 ? "Adult" : "Minor";
     console.log(status); // Output: "Adult"
     ```

7. JavaScript typeof Operator:

   - Definition: Used to determine the data type of a value.
   - Examples:

     ```javascript
     let num = 21;
     let name = "Jayanth";
     let isActive = true;

     console.log(typeof num); // Output: "number"
     console.log(typeof name); // Output: "string"
     console.log(typeof isActive); // Output: "boolean"
     ```

These are some of the essential JavaScript operators with their definitions and simple examples to illustrate their usage.
