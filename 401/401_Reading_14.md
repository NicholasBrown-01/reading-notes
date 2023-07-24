[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 14
<br>

## Intro to password hashing
<br>

1. Define the term “hashing”.
<br>
- The ability to map data of any size into a bit string of a specified size.

2. Explain to a non-technical friend what a hash function does to a password.
<br>
- It's like having a secrete language converter or translator with the computer. You type in your password, but the computer does not save it exactly how you typed it. Instead is scrambles it all up in case someone ever gets access they cannot see your actual password.

## bcrypt overview
<br>

1. What does it mean to ‘salt’ a password?
<br>
- This adds another layer of complexity as it involves including additional characters to your password to also be hashed. 

2. What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?
<br>
- They would have to have access to your source code.

## jBCrypt 
<br>

1.How does the Blowfish block cipher handle the increased computation speed of new computers?
<br>
- The webisite states that the computation cost of the algorithm is parametised so it can be increased as computers get faster.

2. What are the issues with the two most commong password hashes for Java (“Java password hash” and “Java password encryption”)?  
<br>
- Lack of good passwork hashes in this case means one uses unsalted hash and the other reverse encryption.


<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>