[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 13
<br>

## Local Storage and How To Use It On Websites
<br>

1. Why would a developer use local storage for a web application?

<br>
There are a few reasons, but I believe the most beneficial ones are Offline Storage, and better performance...especially when developing a new program or site. Constant loading and saving to a server can cut down a lot of time.

2. What information should not be stored in local storage?

<br>
Things such as sensitive information, payment information, or personal identification information. Thus, things like preferences or administrative data should be stored in local storage.

3. Local storage can store what type of data? How would you convert it to that type before storing?
<br>

As far as "data types" it can store strings, but numbers, arrays, objects etc must be converted before storing.

`var myNumber = 12;
localStorage.setItem('myNumber', myNumber.toString());`

is an example of how to convert a number to a string.




<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>