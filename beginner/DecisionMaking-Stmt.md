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
* __Flowchart__ <br> <br>
![Dig8](https://raw.githubusercontent.com/sangam14/JavaLabs/master/img/Dig8.png)
  

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

### 2) if else
* It is the type of decision making statement.
* It will check the given condition first, if the condition is true then only it will execute the statements which are present in the if block and if the condition is false that time it will execute the statements present inside else block.
* __Syntax__
```
if (condition)
statement;
else 
statement;
```
```
if (condition)
{
    statement1;
    statement2;
}
else
{
    statement3;
    statement4;
}
```
* __Flowchart__ <br> <br>
![Dig9]()

* e.g.
```
class Program1
{
    public static void main (String[]args)
    {
        System.out.println("Hi");
        if (true)    
        System.out.println("Hello");
        else
        System.out.println("By");
    }
}
```
* Ans = Hi, Hello

* e.g.
```
class Program2
{
    public static void main (String[]args)
    {
        System.out.println("Goa Plan");
        if (false)    
        {
            System.out.println("Ask Money");
            System.out.println("Enjoy Goa");
            System.out.println("Come Back Home");
        }
        else
        {
            System.out.println("Plan Fails");
            System.out.println("No Money");
            System.out.println("Sit in Home");
        }
    }
}
```
* Ans = Goa Plan, Plan Fails, No Money, Sit in Home

* __Que.__ Write a program to check whether the given number is divisible by 3 & 7. If it is divisible then display pass else fail.
* Number = 21

```
class Que1
{
    public static void main (String[]args)
    {
        int num = 21;
        if (num % 3 == 0 && num % 7 == 0)    
        {
            System.out.println("Pass");
        }
        else
        {
            System.out.println("Fail");
        }
    }
}
```
* Ans = Pass

* __Que.__ Write a program to check whether the given number even or odd.
* Number = 20

```
class Que2
{
    public static void main (String[]args)
    {
        int num = 20;
        if (num % 2 == 0)    
        {
            System.out.println("Given number is even number");
        }
        else
        {
            System.out.println("Given number is odd number");
        }
    }
}
```
* Ans = Given number is even number

### 2) else if ladder / if-else-if
