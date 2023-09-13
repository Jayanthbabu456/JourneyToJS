# Map,Filter,Reduce

1. **Map in JavaScript:**

   - **Definition:** The `map` method applies a given operation to each element of an array and returns a new array containing the result. It converts elements of one array to another using the given function.

   - **For example:**
     ```Available JavaScript
     // The map to use to double each element in the array
     const number = [1, 2, 3, 4, 5];
     const double = counter.map((x) => x * 2);
     console.log(double); // Output [2, 4, 6, 8, 100].
     ```

2. **Filter in JavaScript:**

   - **Definition:** The `filter` method applies a given function to each element of an array and returns a new array containing only those elements for which the function returns `true` this is used to remove elements based on a condition.

   - **For example:**
     ```Available JavaScript
     // Apply filter to get even numbers from array
     const number = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
     const forNumber = number.filter((x) => x %2 === 0);
     console.log(for); // Output [2, 4, 6, 8, 100].
     ```

3. **Reduce to JavaScript:**

   - **Definition:** The `reduce` method takes a callback function and applies it cumulatively to the elements of an array, reducing the array to a single value. In turn, it is used to collect valuables.

   - **For example:**
     ```Available JavaScript
     // Using reduce to calculate the result of elements in an array
     const number = [1, 2, 3, 4, 5];
     const product = numeric.reduce((x, y) => x * y);
     console.log(product); // Output: 120 (1*2*3*4*5)
     ```
