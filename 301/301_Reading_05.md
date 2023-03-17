[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 05
<br>

## React Docs - Thinking in React
<br>

1. What is the single responsibility principle and how does it apply to components?
<br>
- This is the idea that prefers an component, function, module etc to have only One Responsibility or reason to change. If it becomes more complex, it should then be broken down further.

2. What does it mean to build a ‘static’ version of your application?
<br>
- Here we are focused only on Structure, Elements, and any other arguements or properties that are needed. We do not handle any static changes or data tranfers.

3. Once you have a static application, what do you need to add?
<br>
- Now it is time to focus on making the necessary elements interactive. Still not transferring data.

4. What are the three questions you can ask to determine if something is state?
<br>

> - Does it remain unchanged over time? If so, it isn’t state. <br>
> - Is it passed in from a parent via props? If so, it isn’t state. <br>
> - Can you compute it based on existing state or props in your component?<br>
>  ...If so, it definitely isn’t state!"


5. How can you identify where state needs to live?
<br>
- Identify components that use state
- Find their common parent
- Decide where to place the state in that parent component


## Higher-Order Functions

1. What is a “higher-order function”?
<br>
> - Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. 

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
<br>
- It returns a function that compares "m" with the provided "n", if "m" is greater than "n", true is returned, otherwise false.

3. Explain how either map or reduce operates, with regards to higher-order functions.
<br>
- The 'map()' is a higher-order function because it works on an array and can also take in a function as its argument. The 'map()' function takes in an array and returns a new array while the original array remains unchanged.

<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>