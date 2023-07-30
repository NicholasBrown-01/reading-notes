[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 16
<br>

## Spring Security overview
<br>


1. What does it mean to authenticate a user?
<br>
- Authentication revolves around ensuring the user is who they claim to be. This is done through User Credentials such a login/pass or other means such as google authentiation etc.

2. What does it mean to authorize a user?
<br>
- Once authentication is complete, the resources or privelages a used has are authorized in accordance with the program.

3. What are the three possible outcomes of the AuthenticationManager’s authenticate() method?
<br>
- Return an Authentication (normally with authenticated=true) if it can verify that the input represents a valid principal.
- Throw an AuthenticationException if it believes that the input represents an invalid principal.
-Return null if it cannot decide.

[SpringIO](https://spring.io/guides/topicals/spring-security-architecture/)


## Spring Auth cheat sheet

1. Review the cheatsheet:
<br>

[SpringCheatSheet](https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md)





<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>