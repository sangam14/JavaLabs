## Control Transfer Statements 
* It is used to transfer the control of execution.
* It is classified into
1) break
2) continue

### 1) break
* It is a control transfer statement.
* It is used to transfer the control of execution out of the block.
* It is used to terminate execution flow of looping statement.
* We can not used break keyword within only decision making statement.It must be inside looping statements, otherwise it will compile time error.

```
class Example1
{
    public static void main(String[]args)
    {
        int a = 0;
        while (a < 5)
        {
            System.out.println("*");
            a++;
            break;
        }
    }
}
```
* Ans =  *

```
class Example2
{
    public static void main(String[]args)
    {
        int a = 0;
        while (a < 7)
        {
            System.out.println(a);
            if (a == 3)
            {
                a++;
                System.out.println(a);
                break;
            }
            a++;
        }
    }
}
```
* Ans = 0 <br> 1 <br> 2 <br> 3 <br> 4 <br>

```
class Example3
{
    public static void main(String[]args)
    {
        int a = 1;
        while (a <= 10)
        {
            System.out.print(a);
            if (a == 8)
            {
                System.out.println(a);
                break;
            }
            a++;
        }
    }
}
```
* Ans = 123456788 <br>

### Rules for break statement 
1) break statement should be always at the end of the block.
2) We can not used break in between the block. It will shows compile time error (unreachable statement)

```
class Example4
{
    public static void main(String[]args)
    {
        int a = 0;
        while (a < 7)
        {
            System.out.print(a);
            if (a == 3)
            {
                System.out.println(a);
                break;
                a++;
            }
            a++;
        }
    }
}
```
* Ans = Compile Time Error
