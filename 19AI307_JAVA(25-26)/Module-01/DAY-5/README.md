# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:

Write a java program to check whether a string is a palindrome.

Example:
```
-----------------------------------
Input	       Result 
madam    |  madam is a palindrome.
-----------------------------------

```

## AIM:

To write a Java program to verify if a string reads the same forward and backward using string operations.

## ALGORITHM :

1.Start the program.

2.Import the package java.util.Scanner.

3.Read a string from the user.

4.Reverse the string using a loop.

5.Compare the original string with the reversed string.

6.If both are equal, display that the string is a palindrome; otherwise, display not a palindrome.

7.Stop the program.


## PROGRAM:
 ```

Program to implement a Strings and Math Function using Java
Developed by: JYESVANTHE V
RegisterNumber:  212223110018

```

## SOURCE CODE:
```java

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String str = sc.nextLine();
        String reversed = "";

        for (int i = str.length() - 1; i >= 0; i--) {
            reversed += str.charAt(i);
        }

        if (str.equals(reversed)) {
            System.out.println(str + " is a palindrome.");
        } else {
            System.out.println(str + " is not a palindrome.");
        }
    }
}

```

## OUTPUT:

<img width="595" height="211" alt="Screenshot 2025-11-17 002153" src="https://github.com/user-attachments/assets/894923c6-f8b8-4923-83ce-d35f96eb8116" />


## RESULT:

Thus, the Java program to check whether a string is a palindrome was executed successfully.

