[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 02
<br>

## Java Imports
<br>

1. Use an analogy to explain Built-In packages. Give examples.
<br>
- In short, they are just containers that hold certain types of utilities or packages. Similar to if you had organized tool boxes containing certain tools for certain types of work.

2. Explain the steps for creating a new package in IntelliJ.
<br>
- Bringing in a package is under the 'File' tab followed by 'New' and the 'Package'.

## Different types of loops in Java
<br>

1. Which loop types use a loop counter?
<br>
- Common loops that utilize a counter are the 'for' and 'while' loops.

2. Explain the difference between While and Do-While loops.
<br>
- In a 'while loop' the condition for executing the loop is check before each iteration...if false...it is skipped. 'Do-while loops' are checked at the end. This also means that it WILL be run at least once regardless if the condition is false or not.
<br>

## Java Arrays
<br>

1. Describe 3 built-in methods for Arrays.
<br>
- There are over 20 methods for Arrays in Java: [GeeksforGeeks Info](https://www.geeksforgeeks.org/array-class-in-java)
<br>

| Method                                                 | Description                                                                                                                 |
|--------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| asList()                                               | Returns a fixed-size list backed by the specified array.                                                                    |
| binarySearch()                                         | Searches for the specified element in the array using the Binary Search Algorithm.                                          |
| binarySearch(array, fromIndex, toIndex, key, Comparator)| Searches a range of the specified array using the Binary Search Algorithm and a custom Comparator.                          |
| compare(array1, array2)                                | Compares two arrays lexicographically.                                                                                      |
| copyOf(originalArray, newLength)                       | Copies the specified array, truncating or padding with the default value to achieve the specified length.                   |
| copyOfRange(originalArray, fromIndex, endIndex)        | Copies the specified range of the array into a new array.                                                                   |
| deepEquals(Object[] a1, Object[] a2)                   | Checks if the two specified arrays are deeply equal to each other.                                                          |
| deepHashCode(Object[] a)                               | Returns a hash code based on the "deep contents" of the specified array.                                                    |
| deepToString(Object[] a)                               | Returns a string representation of the "deep contents" of the specified array.                                              |
| equals(array1, array2)                                 | Checks if two arrays are equal.                                                                                             |
| fill(originalArray, fillValue)                         | Assigns the fill value to each index of the array.                                                                          |
| hashCode(originalArray)                                | Returns the integer hash code of the array.                                                                                 |
| mismatch(array1, array2)                               | Finds and returns the index of the first unmatched element between the two specified arrays.                               |
| parallelPrefix(originalArray, fromIndex, endIndex, functionalOperator) | Performs parallelPrefix on the specified range of the array using the provided functional operator.          |
| parallelPrefix(originalArray, operator)                | Performs parallelPrefix on the entire array using the provided functional operator.                                         |
| parallelSetAll(originalArray, functionalGenerator)     | Sets all the elements of the array in parallel using the provided generator function.                                      |
| parallelSort(originalArray)                            | Sorts the specified array using parallel sort.                                                                              |
| setAll(originalArray, functionalGenerator)             | Sets all the elements of the specified array using the generator function provided.                                        |
| sort(originalArray)                                    | Sorts the entire array in ascending order.                                                                                  |
| sort(originalArray, fromIndex, endIndex)               | Sorts the specified range of the array in ascending order.                                                                  |
| sort(T[] a, int fromIndex, int toIndex, Comparator< super T> c) | Sorts the specified range of the array of objects using the specified comparator.                                  |
| sort(T[] a, Comparator< super T> c)                    | Sorts the specified array of objects using the specified comparator.                                                        |
| spliterator(originalArray)                             | Returns a Spliterator covering all of the specified array.                                                                  |
| spliterator(originalArray, fromIndex, endIndex)        | Returns a Spliterator covering the specified range of the array.                                                            |
| stream(originalArray)                                  | Returns a sequential stream with the specified array as its source.                                                         |
| toString(originalArray)                                | Returns a string representation of the contents of the array.                                                               |


2. How is the size of an array determined in Java?
<br>
- It is set be the size when the array is created.
Ex: 'int[] foodItems = new foodItems[5];'



<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>