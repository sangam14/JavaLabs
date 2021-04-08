### Looping Statements 
* It is the type of the control flow statement which will execute the group of statements multiple times by checking the condition in each time.
* Looping statement is classified into 
1) for loop
2) while loop
3) do while loop

### 1) for loop 
* It is the type of looping statements which will have fix initial and final point to execute the given statements multiple times.
* __Syntax__
![ForSyntax]()

* __Que__ Print "*" four times.

```
class Que1
{
    public static void main(String[]args)
    {
        for (int i = 0; i < 4; i++)
        {
            System.out.println("*");
        }
    }
}
```
* __Que__ Write the program to print even number between 100 to 80 using for loop.

```
class Que1
{
    public static void main(String[]args)
    {
        for (int i = 100; i >= 800; i--)
        {
            if (i % 2 == 0)
            {
                System.out.println(i);
            }
        }
    }
}
```

