[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 12
<br>

## Spring guide: Accessing Data with JPA

1. How are query methods defined when using Spring Data JPA?
<br>
- Via naming convetion for the work/repository. You can also utilize method signatures.

2. Which dependencies will you need in order to complete the Spring guide?
<br>
- H2 Database and Spring Data JPA

3. What annotations are used to specify an auto generated identification number for an Entity?
<br>
- I believe this is the '@GeneratedValue'.



## Baeldung: Comparing repositories
<br>

1. Which of the Spring Data Repositories covered in the readings has the most methods available to it?
<br>
- JPA Repository

2. Name a downside of a Spring Data Repository.
<br>
- Lack of control due to extending the CrudRepository all at once.

3. How would you define an operation to find a student based on their name in a repo named StudentRepository which extends JpaRepository?
<br>

public interface StudentRepository<T, ID extends JpaRepository>

    List<T> findByName(name);

Is about all I could figure out based on the article.


<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>