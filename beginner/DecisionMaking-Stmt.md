## Decision Making Statements 
* It is the type of control flow statements which will check the given condition before performing a perticular task.
* It is classified into <br>
1) if (simple if)
2) if else
3) else if ladder
4) nested if
5) switch

### 1) if (simple if)
* It is the type of decision making statement.
* It is a keyword in java.
* It will check the given condition first, if the condition is true then only it will execute the statements which are present in the if block.
* __Syntax__
```
if (condition)
statement1;
```
```
if (condition)
{
    statement1;
    statement2;
}
```
* e.g.
```
class Program1
{
    public static void main (String[]args)
    {
        System.out.println("Hi");
        if (true)    
        System.out.println("Hello");
        System.out.println("My name is Sunil");
    }
}
```
* Ans = Hi, Hello, My name is Sunil

```
class Program2
{
    public static void main (String[]args)
    {
        System.out.println("Hi");
        if (false)
        System.out.println("Hello");
        System.out.println("My name is Sunil");
    }
}
```
* Ans = Hi, My name is Sunil

```
class Program3
{
    public static void main (String[]args)
    {
        System.out.println("Hi");
        if (true)
        {
            System.out.println("Hello");
            System.out.println("Please Reply...");
        }
        System.out.println("Block")
    }
}
```
* Ans = Hi, Hello, Please Reply..

```
class Program3
{
    public static void main (String[]args)
    {
        System.out.println("Hi");
        if (true)
        {
            System.out.println("Hello");
            System.out.println("Please Reply...");
        }
        System.out.println("Block")
    }
}
```
* Ans = Hi, Hello, Please Reply.., Block

```
class Program4
{
    public static void main (String[]args)
    {
        System.out.println("Hi");
        if (false)
        {
            System.out.println("Hello");
            System.out.println("Please Reply...");
        }
        System.out.println("Block")
    }
}
```
* Ans = Hi, Block
