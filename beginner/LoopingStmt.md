### Looping Statements 
* It is the type of the control flow statement which will execute the group of statements multiple times by checking the condition in each time.
* Looping statement is classified into 
1) for loop
2) while loop
3) do while loop

### 1) for loop 
* It is the type of looping statements which will have fix initial and final point to execute the given statements multiple times.
* __Syntax__ <br> <br> <br>
![ForSyntax](https://raw.githubusercontent.com/sangam14/JavaLabs/master/img/forSyntax.png)

* __Que1__ Print "*" four times.

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
* __Que2__ Write the program to print even number between 100 to 80 using for loop.

```
class Que2
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
* __Que3__ Write the program to find summation of first ten numbers starting from 1.

```
class Que3
{
    public static void main(String[]args)
    {
        int sum = 0;
        for (int i = 1; i <= 10; i++)
        {
            sum = sum + i;
        }
        System.out.println(sum);
    }
}
```
* Ans = 55

* __Que4__ Write the program to find summation of all even numbers between 20 to 10 using for loop.

```
class Que4
{
    public static void main(String[]args)
    {
        int sum = 0;
        for (int i = 20; i >= 10; i--)
        {
            if(i % 2 == 0 )
            {
                sum = sum + i;
            }
        }
        System.out.println(sum);
    }
}
```
* Ans = 90

### 2) while loop



