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
1) break statement should be always at the end of the block. <br>
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

### 2) continue
* It is keyword in java.
* continue helps to transfer the control of execution beginning of the condition.
* It is used to skip the execution of looping statement without terminating it.
* continue keyword must be written within looping statement. We can not written continue keyword only within decision making statement.

```
class Continue1
{
    public static void main(String[]args)
    {
        for(int i = 1; i <= 10; i++)
        {
            if(i == 5)
            {
                continue;
            }
            System.out.print(i+" ");
        }
    }
}
```
* Ans = 1 2 3 4 6 7 8 9 10 