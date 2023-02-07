[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 03
<br>

### Learn HTML

#### Ordered and Unordered lists
<br>

1. When should you use an unordered list in your HTML document?
<br>
- When the information in the list does not benefit from any type of sorting, numbering, or order of any kind.

2. How do you change the bullet style of unordered list items?
<br>
- This is based on how the unordered list is nested.

3. When should you use an ordered list vs an unorder list in your HTML document?
<br>
- If the information can be more clearly understood, read, or followed by having a defined number, order, sequence than an ordered list should be used. Otherwise unordered is acceptable.


4. Describe two ways you can change the numbers on list items provided by an ordered list?
<br>
- You can change the style to roman numberal by specifying "i" in the `<ol type="i">` command. The starting number can also be changed, such as `<ol start="8">`.

### Learn CSS
<br>

#### The Box Model

1. Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?
<br>
- Once upon a time there were 2 sisters, Margin and Padding. They were very particular when it came to giving each other space. Margin only cared about how far apart they were from the edges of their shape. Padding only wanted to focus on how much room there was from their core box to the edge.

2. List and describe the four parts of an HTML elements box as referred to by the box model.
<br>

The following information is provided by: [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

- Content box: The area where your content is displayed; size it using properties like `inline-siz`e and `block-size` or width and height.

- Padding box: The padding sits around the content as white space; size it using `padding` and related properties.

- Border box: The border box wraps the content and any padding; size it using `border` and related properties.

- Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using `margin` and related properties.

### Learn JS

#### Arrays. Operators and Expressions. Conditionals. Loops.
<br>

1. What data types can you store inside of an Array?
<br>
- Anything... Strings, other arrays, numbers, and objects.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
<br>
- Yes. Use the command `console.log(people)` to access the information.
<br>

3. List five shorthand operators for assignment in javascript and describe what they do.
<br>

- `x ||= f()` is a Logical OR assignment
- `x &&= f()` is a Logical AND assignment
- `x |= f()` is a Bitwise OR assignment
- `x ^= f()` is a Bitwise XOR assignment
- `x &= f()` is a Bitwise AND assignment

4. Read the code below and evaluate the last expression and explain what the result would be and why.
<br>
- The results are "10dog" for combining "a" a string and "c" a boolean. Resulting in "10", then adding the string "dog".

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
<br>
- Meeting a password requirement to gain further access into a system/program.

6. Give an example of when a Loop is useful in JavaScript.
- If a user was to answer outside the required/specified parameters of a prompt, they can be re-introduced to the original prompt to try again.

<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>