[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 36
<br>

## Amplify & Cognito
<br>


1. Where in your application should you check the current auth session?
<br>
- After Initializing you can run the following in the MainActivity:

```
 Amplify.Auth.fetchAuthSession(
    result -> Log.i("AmplifyQuickstart", result.toString()),
    error -> Log.e("AmplifyQuickstart", error.toString())
);
```

2. What is the command that is used to push your changes to the cloud?
<br>
- ```amplify push```

3. What does Amplify Auth do for your application?
<br>
- In short it is an interface used to verify/authenticate a user.


<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>