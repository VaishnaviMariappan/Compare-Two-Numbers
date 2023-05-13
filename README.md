# EXP-2 Java program to compare two numbers

## Aim:

To Write a Java program to compare two numbers

## Algorithm:

1. Declare two variables to hold the numbers you want to compare.
 
2. Use an if-else statement to compare the numbers.
 
3. If the first number is greater than the second number, print a message indicating that the first number is greater.
 
4. If the second number is greater than the first number, print a message indicating that the second number is greater.

5. If the numbers are equal, print a message indicating that the numbers are equal.

## Program:
``` java
import java.util.Scanner;
import java.util.Scanner;
public class compare
{
    public static void main(String[] args)
    {
        Scanner a = new Scanner(System.in);
        Integer num1 = a.nextInt();
        Scanner b = new Scanner(System.in);
        Integer num2 = b.nextInt();
        if (num1 > num2)
        {
            System.out.println(num1 + " is greater than " + num2);
        }
        else if (num1 < num2)
        {
            System.out.println(num1 + " is lesser than " + num2);
        }
        else
        {
            System.out.println("The numbers are equal");
        }
    }
}
```
## Output:
![image](https://github.com/VaishnaviMariappan/Compare-Two-Numbers/assets/94169913/9f150eb1-34c4-4c95-bddf-e4513dc77782)

## Result:

Thus, a Java program is written to compare two numbers.
