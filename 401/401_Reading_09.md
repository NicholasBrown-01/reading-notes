[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 09
<br>

## High Level HTTP
<br>

1. What are the five steps in the HTTP Request Lifecycle?
<br>
- Local Processing
- Resolve an IP
- Establish TCP Connection
- Send an HTTP Request
- Send and Process Response

2. What are the two things the client needs before it can make an HTTP Request?
<br>
- Server Address (URL or IP)
- Request Method (GET, POST, PUT, DELETE etc)

3. Explain the four way handshake and what it does.
<br>
- Overall, it is the system in which a secure connection is made and ended via the Transport Layer Security. It is a check on both the client and the server to ensure integrity is maintained between the two.


## Java HTTP
<br>

1. True or False: When making an HTTP request, you MUST follow any redirect returned by the request. Back up your answer.
<br>
- False. By DEFAULT this behavior is enabled, however, the instance can be manually set to not accept automatic redirects. While this means you will not be able to retrieve data (hence the suggested redirect for your client request from the server) it is not a MUST...as in there is no other options or setting what-so-ever.

2. Which built-in Java class can be used to perform an HTTP request?
<br>
 - 'java.net.HttpURLConnection'

3. What HTTP status codes represent a successful response? A redirect? A client error?
<br>
 - 200
 - 300
 - 400


<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>