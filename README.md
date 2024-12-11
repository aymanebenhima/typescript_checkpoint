# TypeScript Exercise: Implementing Interfaces and Classes

## **Objective**
Follow the instructions below to complete the exercise. This will help you practice creating and using interfaces, implementing classes, and compiling TypeScript code.

---

## **Instructions**

1. **Define an Interface:**
   - Create an interface named `Vehicle` with the following properties and methods:
     - `make` of type `string`.
     - `model` of type `string`.
     - `year` of type `number`.
     - `start` method which returns `void` and logs **"Engine started"** to the console.

2. **Implement a Class:**
   - Define a class named `Car` that implements the `Vehicle` interface.
   - The `Car` class should have:
     - A constructor that initializes the `make`, `model`, and `year` properties.
     - An implementation of the `start` method to log **"Car engine started"** to the console.

3. **Create an Instance:**
   - Create an instance of the `Car` class with appropriate values for `make`, `model`, and `year`.

4. **Call the Method:**
   - Call the `start` method on the instance of the `Car` class to verify that it logs the appropriate message to the console.

5. **Compile and Run:**
   - Compile your TypeScript code into JavaScript using the TypeScript compiler (`tsc` command).
   - Run the resulting JavaScript code in Node.js or a browser to ensure everything works as expected.

---

## **Hints**

- **Hint 1:** Use the `interface` keyword to define the structure of the `Vehicle` interface.

- **Hint 2:** When implementing the `Vehicle` interface in the `Car` class, ensure that all properties and methods are present and correctly typed.

- **Hint 3:** To create an instance of the `Car` class, use the `new` keyword and pass the required parameters.

- **Hint 4:** Use the TypeScript compiler to transpile your `.ts` file into a `.js` file.

- **Hint 5:** Run the resulting JavaScript file using Node.js or include it in an HTML file for testing in the browser.

---

## **Expected Output**
When you run the program, the console should display the following message:
```
Car engine started
```

---

## **Additional Challenge**
After completing the exercise, extend the `Vehicle` interface and `Car` class:
- Add a `stop` method to the `Vehicle` interface that logs **"Engine stopped"**.
- Implement the `stop` method in the `Car` class.
- Call the `stop` method on the `Car` instance to ensure it works as expected.

---

Happy coding! 🚗✨
