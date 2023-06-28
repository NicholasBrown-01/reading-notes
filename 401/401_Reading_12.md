[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 12
<br>

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:
<br>

100’s = Informative status code
<br>
200’s = A request has been successfully processed
<br>
300’s = Additional Action Required
<br>
400’s = Bad request was made
<br>
500’s = Server error
<br>

2. What is a status code 202?
<br>
- Request accepted but not complete

3. What is a status code 308?
<br>
- Different URL needed

4. What code would you use if an update didn’t return data to a client?
<br>
- 204 No Content

5. What code would you use if a resource used to exist but no longer does?
<br>
- 410 Gone

6. What is the ‘Forbidden’ status code?
<br>
- 403 Forbidden


## Build A REST API With Node.js, Express, & MongoDB
<br>

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
<br>
- Because we put sensitive information into our .env

2. What is middleware?
<br>
- Functions that can modify/intercept requests and responses in Express.js.

3. What does `app.use(express.json())` do?
<br>
- It is Middleware the parses incoming JSON data and makes it available to the request object.

4. What does the /:id mean in a route?
<br>
- It can extract a value from the URL.

5. What is the difference between `PUT` and `PATCH?`
<br>
- They are HTTP methods, PUT replaces an existing resource with a new one. PATCH updates a resource with new data only.

6. How do you make a default value in a schema?
<br>
- Use the `default` property when defining the schema.

7. What does a `500` error status code mean?
<br>
- Server Side Error

8. What is the difference between a status `200` and a status `201`?
<br>
- 200 (GET) means a requst was successful, 201 means the request has been created on the server and a resource has been created, such as POST, PUT and PATCH.

<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>