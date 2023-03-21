[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 10
<br>

## Understanding the JavaScript Call Stack

1. What is a ‘call’?
<br>
- A call is the means by which a function is invoked. 

2. How many ‘calls’ can happen at once?
<br>
- In JavaScript, only 1 call can happen at a time.

3. What does LIFO mean?
<br>
- This term means Last In First Out -- referring to the order in which calls are executed in the stack.

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
<br>

> function firstFunction(){ <br>
> console.log("Hello from firstFunction"); <br>
> }<br> 
>
> function secondFunction(){ <br>
>  firstFunction(); <br>
>  console.log("The end from secondFunction"); <br>
> } <br>
>
> secondFunction(); <br>

5. What causes a Stack Overflow?
<br>
- This occurs when a call stack exceeds the maximum size causing a crash. This normally happens if functions never terminate and too many run.

## JavaScript error messages
<br>

1. What is a ‘reference error’?
<br>
- A variable or function is referenced but not defined.

2. What is a ‘syntax error’?
<br>
- Code violates the language syntax rule and cannot be executed.

3. What is a ‘range error’?
<br>
- A value is outside the acceptable range such as with arrays being too large etc.

4. What is a ‘type error’?
<br>
- value of the wrong type for the operation that is being performed.

5. What is a breakpoint?
<br>
- This is associated with a debugger session at which point the test will stop on this specific line.

6. What does the word ‘debugger’ do in your code?
<br>
- this will manually set a breakpoint allowing a test to pause for inspection.


<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>