[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 37
<br>

## Amazon S3
<br>


## Amplify & Cognito
<br>


1. What is Amazon S3?
<br>
- It is a "Simple Storage Service" that has scalibility, security, and performance.

2. List at least 3 features that it offers to its users.
<br>
- Storage Management: Lifecycle, Object Lock, Replication, Batch Operations
- Security: Block Public Access, AWS IAM, Bucket Policies, ACLs
- Data Processing: Object Lambda, Event Notification

3. What is an object key?
<br>
- It is also known as a key name, which is a unique ID for an object with a bucket.


## S3 with Amplify
<br>


1. Which dependencies are needed to install Amplify AWS S3 to your ndroid application?
<br>
- ```dependencies {
    implementation 'com.amplifyframework:aws-storage-s3:2.12.0'
    implementation 'com.amplifyframework:aws-auth-cognito:2.12.0'
}```

2. What is needed in order to upload data to your bucket?
<br>
- You must specify the key and the data object to be uploaded.

3. What method(s) initialize(s) the Amplify Auth and Storage categories?
<br>
- Amplify.Auth & Amplify.Storage



<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>