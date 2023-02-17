[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 10
<br>

## What Went Wrong? Troubleshooting JavaScript
<br>

1. Name some key differences between a Syntax Error and a Logic Error.
<br>
A Logic Error is when a desired output or value is not produced while a Syntax Error regards the code violating a sytax rule of the programming language.


2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
<br>
I had a logic error that was causing my footer to not be removed from my table, more specifically the Totals colums was being recreated every time a user input a new city....even though I thought I had the code right to remove that exact line. It turned out, that while I was calling the name of my table in the html, I had to add `tbody` to the querySelector because JS didn't understand that it needed to target the last row of the table in my JS table creation vs a physical tag in the html...because we created the table via JS...it didn't see anything to remove.


3. How will this topic continue to influence your long term goals?
<br>
Syntax and logic errors I assume will be a major part of our careers moving forward. Thus the better we are able to identify and troubleshoot them the more successful we will be.


## The JavaScript Debugger
<br>

1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
<br>
It allows for specific testing in areas that we define in our code to ensure these setions are working correctly.

2. Define what a breakpoint is.
<br>
A breakpoint acts as a "stop sign" for the debugger. It will run until that point and the "stop" or "break" to prevent the program from continuing to run through your entire code.

3. What is the call stack?
<br>
It simply tell us the code that was actually executed to get the the current line you are on.

<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>