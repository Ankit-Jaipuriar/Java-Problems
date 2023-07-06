# if-else-else if
## Task
Given an integer, , perform the following conditional actions:

If n is odd, print Weird.

If n is even and in the inclusive range of 2 to 5, print Not Weird.

If n is even and in the inclusive range of 6 to 20, print Weird.

If n is even and greater than 20, print Not Weird.

## solution
```java
import java.util.*;
public class Solution {

    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        if(a%2==0){
            if(a>=2 && a<=5){
            System.out.println("Not Weird");
        }
        else if(a>=6 && a<=20){
            System.out.println("Weird");
            
        }
        else{
            System.out.println("Not Weird");
        }
        }
        else{
            System.out.println("Weird");
        }
        
    }
}
```
**[Try it on Hackerrank](https://www.hackerrank.com/challenges/java-if-else/problem?isFullScreen=true&h_r=next-challenge&h_v=zen&h_r=next-challenge&h_v=zen)**
