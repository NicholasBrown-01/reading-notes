[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 03
<br>

### Learn HTML

#### React Docs - lists and keys
<br>

1. What does .map() return?
<br>
- Whatever is in the assigned array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
<br>
- Use your old array combined with the .map() method to then display each value into a html property syntax

3. Each list item needs a unique ____.
<br>
- key

4. What is the purpose of a key?
<br>
- They help identify things that have changed, been added or removed.


### The Spread Operator
<br>

1. What is the spread operator?
<br>
- It is JavaScript syntax used to manipulate and manage data in an array. 

2. List 4 things that the spread operator can do.
<br>
- Combine arrays, Combine objects, adding items to an array, or spreading it out.

3. Give an example of using the spread operator to combine two arrays.
<br>
*From https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab*

- const myArray = [`🤪`,`🐻`,`🎌`] <br>
const yourArray = [`🙂`,`🤗`,`🤩`]<br>
const ourArray = [...myArray,...yourArray]<br>
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩<br>

4. Give an example of using the spread operator to add a new item to an array.
<br>
*From https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab*
- const fewFruit = ['🍏','🍊','🍌'] <br>
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]<br>
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]<br>

5. Give an example of using the spread operator to combine two objects into one.
<br>
*From https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab*

- const objectOne = {hello: "🤪"}<br>
const objectTwo = {world: "🐻"}<br>
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}<br>
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }<br>
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}<br>
objectFour.laugh() // 😂😂😂😂😂<br>

### How to Pass Functions Between Components
<br>

1. In the video, what is the first step that the developer does to pass functions between components?
<br>
- He places the function between the parent and the child.

2. In your own words, what does the increment function do?
<br>
- It increases the value of a variable by a specific amount.

3. How can you pass a method from a parent component into a child component?
<br>
- 'increment={this.increment}'

4. How does the child component invoke a method that was passed to it from a parent component?
<br>
- You can make the increment a prop that is called Ex: 'this.props.increment()'


<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>