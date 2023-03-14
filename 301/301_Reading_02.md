[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 02
<br>

### React Lifecycle
<br>

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
<br>
- The render happens first as Order of Operations is Top to Bottom.

2. What is the very first thing to happen in the lifecycle of React?
<br>
- of the 3 phases: Mounting, Updating, and Unmounting....Mounting occurs first.

3. Put the following things in the order that they happen:
<br>
- Constructor
- Render
- React Updates
- componentDidMount
- componentWillUnmount

4. What does 'componentDidMount' do?
<br>

- It is used to initialize the DOM or load data via the netword request. It must also be unsubscribed via the 'componentWillUnmount()'

### React State Vs Props
<br>

1. What types of things can you pass in the props?
<br>
- Anything that would normally be an "arguement" in a function. What you want your component to render.

2. What is the big difference between props and state?
<br>
- Props are arguements to a "function" and handled outside the component, while a state is handled inside the component.

3. When do we re-render our application?
<br>
- States can be updated within the component while props or functions must be rendered outside themselves.

4. What are some examples of things that we could store in state?
<br>
- States can be changed/rendered based on user input such as a title/description/numbers/counters etc. This is especially usefull when utilizing forms. If no parent is used, a State is better suited than a prop.





<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>