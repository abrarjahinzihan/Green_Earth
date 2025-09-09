1.	What is the difference between var, let, and const? ans-
In JavaScript, var, let, and const are all used to declare variables, but they behave differently. var is the oldest method; it's function-scoped and can be redeclared and updated. let and const are newer and block-scoped, meaning they are only accessible within the curly braces {} where they are defined. The main difference between them is that let can be updated after declaration, while const cannot be updated or redeclared—it's for constant values. Modern code typically uses const by default and let only when needing to reassign values, avoiding var altogether.
2.	What is the difference between map(), forEach(), and filter()?
ans- these are all methods to loop over an array, but they are used for different purposes:
forEach(): "Do something with each item." (For actions) it is used when we want to perform an action or side effect for every item in an array Its primary job is to execute a function if we provide once for each element, such as logging each value to the console, updating a DOM element, or sending data to an API. It is the tool we can reach for when the goal is the action itself during the iteration, not the creation of a new data structure.
map(): "Transform each item and get a new array back." (For transformation)
it is used when we need to transform every element in an array and create a new array from the results. Its purpose is to apply a transformation function to each item, effectively "mapping" each original value to a new, corresponding value.
filter(): "Pick which items to keep based on a condition." (For selection)
it is used when we need to select a subset of elements from an array based on a specific condition. It acts as a gatekeeper, testing each element against a function you provide. Its sole job is to decide which items to keep and which to discard, effectively filtering out unwanted values from the collection.
3.	What are arrow functions in ES6?
ans- Arrow functions are a shorter way to write functions in JavaScript, introduced in ES6. They use the => syntax instead of the function keyword, making code more concise, especially for simple one-line functions.
for example
// Traditional function expression const addTraditional = function(a, b) { return a + b; };
// Arrow function equivalent const addArrow = (a, b) => { return a + b; };
// Even shorter for single expressions const addShort = (a, b) => a + b;
4.	How does destructuring assignment work in ES6?
ans- Destructuring in ES6 is a shortcut that lets unpack values from arrays or objects into separate variables quickly. Instead of writing multiple lines to extract each value, we can do it in a single line. For arrays, we use square brackets [] to pull out values by their position. For objects, we use curly braces {} to extract values by their property names. This makes our code cleaner, shorter, and easier to read when you need to work with specific pieces of data from arrays or objects.
5.	Explain template literals in ES6. How are they different from string concatenation?
ans- Template literals use backticks (`) instead of quotes. They allow: String interpolation → insert variables easily using ${ }. Multiline strings → no need for \n
for example
const name = "Zihan"; console.log(Hello, my name is ${name});

