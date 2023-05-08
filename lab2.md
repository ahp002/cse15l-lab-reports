# Week 3 Lab Report 2

## Part 1
`StringServer.java code`

![StringServer](StringServer.png)


`Example 1`

![image](Hello.png)

`Descriptions:`

1. The methods called are the handleRequest method in the ServerHandler class and the main method in the StringServer class.
2. The handleRequest method takes in a url of the type URI as the argument and the main method takes in the port number as the argument. The ServerHandler class has a field called message of the type String and the StringServer class doesn't have any relevant fields.
3. The value of message changes from this request because it changes from an empty String "" to "Hello" and a concatenated line after it.



`Example 2`

![image](urmom.png)

`Descriptions:`


1. The methods called are the handleRequest method in the ServerHandler class and the main method in the StringServer class.
2. The handleRequest method takes in a url of the type URI as the argument and the main method takes in the port number as the argument. The ServerHandler class has a field called message of the type String and the StringServer class doesn't have any relevant fields.
3. The value of message changes from this request because it changes from the String "Hello" and a new concactenated line after it to "Hello", "ur mom" in a new line, and a new concatenated line after it.


## Part 2
Lab 3 Bug: reverseInPlace method
* Failure-Inducing Input
```
public void testReversePlace() {
    int[] input2 = {1, 2, 3};
    ArrayExamples.reverseInPlace(input2);
    assertArrayEquals(new int[]{3, 2, 1}, input2);
  } 
```
* Non Failure-Inducing Input
```
public void testReverseInPlace() {
    int[] input1 = { 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
	}
```
* Symptom


![Symptom](Symptom.png)
* Bug


Before:
```
 static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = arr[arr.length - i - 1];
    }
  }
```
After:
```
static void reverseInPlace(int[] arr) {
    for(int i = 0; i < (arr.length / 2); i += 1) {
      int first = arr[0];
      arr[i] = arr[arr.length - i - 1];
      arr[arr.length - i - 1] = first; 

    }
  }
```

The fix addresses the issue because before, the bug would skip over the element at index 0 so it wouldn't be reversed. After the fix, the element at index 0 would get correctly stored and wouldn't be skipped over when reversing. 


## Part 3
From week 2 in lab, I learned how to make a web server and update it with different numbers in the search bar. It was really interesting to see the web server increment and save its previous value after incrementing it a multitude of times.
