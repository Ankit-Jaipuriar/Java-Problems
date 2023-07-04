# Multiple inputs in a line
Now lets try and solve the following

## Task
Accept 3 space separated integers given in a line into 3 variables - 
A, B and C.
Print them out to a single line on the console

### Solution
```java
public class inputs
{
	public static void main (String[] args)
	{
        Scanner objName = new Scanner(System.in);
        int A = objName.nextInt();
        int B = objName.nextInt();
        int C = objName.nextInt();
		System.out.println(A + " " + B + " " + C);
	}
}
```
**[Try it on Codechef](https://www.codechef.com/learn/BJ00BP01_V2/problems/GSJ206)**
