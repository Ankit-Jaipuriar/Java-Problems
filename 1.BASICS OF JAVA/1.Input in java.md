# Input in Java
Task
In this challenge, you must read  integers from stdin and then print them to stdout. Each integer must be printed on a new line.

Input Format

There are  lines of input, and each line contains a single integer.

Sample Input

42

100

125

Sample Output

42

100

125

## Solution
```java
import java.util.*;
public class input{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int c=sc.nextInt();
        System.out.println(a);
        System.out.println(b);
        System.out.println(c);
    }
}
```
**[Try it on Hackerrank](https://www.hackerrank.com/challenges/java-stdin-and-stdout-1/problem?isFullScreen=true&h_r=next-challenge&h_v=zen)**
