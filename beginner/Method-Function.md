### Method / Function 
* It is a set of instruction to do a perticular task.
* Method/Function are used to avoid duplicate number of lines in program.
### Method Header <br>
![MethodHeader]()

* Method Header consist of : <br>
1) Modifier <br>
2) Return type <br>
3) Method name <br>
4) Formal arguments (datatype variable_name) <br>

* Method Header consist of : <br>
1) Method name <br>
2) formal arguments (datatype variable_name) <br>
* We can have more than one method inside the class block.

### Return Type
* It is simply indicate that what kind of values you return.
* We can return two datatype of values.

__1) Primitive datatype values__
   * byte,short,int,long,float,double,char,boolean. 
  
__2) Non-Primitive datatype values__
   * String, void
__void__
* void is a non-primitive datatype.
* void is a keyword in java.
* void means nothing.
* void does not return any value.

### Method Convension 
1) If the method name consist of single word it should be in terms of lower case. e.g. add()
2) If the method name consist of more than one word (multiword) then the first letter of the second word it should be in terms of upper case. e.g. addSum()

### Formal Arguments 
* Formal arguments are the decleration of variables inside the method header.
* The variables behaves like local veriable.
* The variable did not to be initillized.
* We can initillize the variable from the main/other method by calling particularmethod with the help of method name.

### Note 
1) There is only one main() method in java.
2) Methods (other than main() method) gets executed only when it is called.

```
class Add
{
    public static void add (int a, int b)
    {
        int res = a + b;
        System.out.println(res);
    }
    public static void main (String[] args)
    {
        add(10,20);
        add(10,10);
    }
}
```
* Ans = 30 <br> 20

### Method Calling Statement 
![MethodCallStmt]()

* It is the control trasfer statement.
* It tries to transfer the control from calling method (main() method) to called method (another method).

* __Calling Method__
* The method which tries to call another method is called as calling method.

* __Called Method__
* The method which is under the execution is called as called meth
od.

* __Que1.__ Write a program to print all even numbers between 0 to 50 using method.

```
class EvenFor
{
    public static void even (int a, int b)
    {
        for (int i = a; i <= b; i++)
        {
            if (i % 2 == 0)
            {
                System.out.println(i+ " ");
            }
        }
    }
    public static void main(String[] args)
    {
        even(0,50);
    }
}
```
* __Ans :__ 0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44 46 48 50 

```
class EvenWhile
{
    public static void even (int a, int b)
    {
        while (a <= b)
        {
            if (a % 2 == 0)
            {
                System.out.print(a+ " ");
            }
            a++;
        }
    }
    public static void main(String[] args)
    {
        even(0,50);
    }
}
```
* __Ans :__ 0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44 46 48 50 

* __Que2.__ Write a program to find maximum of three numbers using method.

```
class MaxThree
{
    public static void maxThree (int a, int b, int c)
    {
        int res = a > b && a > c ? a : b > c ? b : c;
        System.out.println(res);
    }
    public static void main(String[] args)
    {
        maxThree(370,100,770);
    }
}
```
* __Ans :__  770

* __Que3.__ Write a program to find summation of all even numbers between 0 to 20 using method.

```
class class SumEvenFor
{
    public static void sumEven (int a, int b)
    {
        int sum = 0;
        for (int i = a; i <= b; i++)
        { 
            if (i % 2 == 0)
            {
               sum = sum + i;
            }
        }
        System.out.println(sum);
    }
    public static void main(String[] args)
    {
        sumEven(0,20);
    }
}
```
* __Ans :__  110

```
class SumEvenWhile
{
    public static void sumEven (int a, int b)
    {
        int sum = 0;
        while (a <= b)
        { 
            if (a % 2 == 0)
            {
               sum = sum + a;
            }
            a++;
        }
        System.out.println(sum);
    }
    public static void main(String[] args)
    {
        sumEven(0,20);
    }
}
```
* __Ans :__  110

### Return Type
1. The process of transfering the control from called method to calling method is called as return type.
2. We can return two data type of values. <br>
   i) Primitive Datatype <br>
   ii) Non-Primitive Datatype

__Note :__ <br>
* By using return type we can reuse called method result into calling statement.

```
class Money
{
    public static int giveLoan (int money)
    {
        System.out.println(money + "to build the bussiness");
        return money;
    }
    public static void main(String[] args)
    {
        int money = giveLoan(10000);
        int totalMoney = money + (money*10/100);
        System.out.println(giveLoan(20000));
        System.out.println("return total amount of money "+totalMoney);
    }
}
```
* __Ans :__ <br> 10000to build the bussiness <br>
20000to build the bussiness <br>
20000 <br>
return total amount of money 11000 <br>

```
class MultiMethod
{
    public static void vidya(int a)
    {
        System.out.println(sanket(12.15));
        return;
    }
    public static boolean sanket(double b)
    {
        System.out.println(nidhi('a'));
        return true;
    }
    public static int nidhi(char ch)
    {
        System.out.println(ch);
        return 10;
    }
    public static void main(String[]args)
    {
        vidya(10);
    }
}
```
* __Ans :__ <br>
a <br>
10 <br>
true

* __Que1.__ Write a program to find maximum of three numbers and return the maximum value.
* Numbers = 30,42,80
```
class ThreeMaxR
{
    public static int max(int a, int b, int c)
    {
        int res = a > b && a > c ? a : b > c ? b : c;
        return res;
    }
    public static void main(String[]args)
    {
        System.out.println(max(30,42,80));
    }
}
```
* __Ans :__ 80

* __Que2.__ Write a program to perform summation of all the numbers between 100 to 50 which are divisible by 3 & 7 and return the sum.
```
class SumDivFor
{
    public static int sumDiv(int a, int b)
    {
        int sum = 0;
        for(int i = a; i >= 50; i--)
        {
            if(i % 3 == 0 && i % 7 == 0)
            {
                sum = sum + i;
            }
        }
        return sum;
    }
    public static void main(String[]args)
    {
        System.out.println(sumDiv(100,50));
    }
}
```
* __Ans :__ 147

```
class SumDivWhile
{
    public static int sumDiv(int a, int b)
    {
        int sum = 0;
        while(a >= b)
        {
            if(a % 3 == 0 && a % 7 == 0)
            {
                sum = sum + a;
            }
            a--;
        }
        return sum;
    }
    public static void main(String[]args)
    {
        System.out.println(sumDiv(100,50));
    }
}
```
* __Ans :__ 147

**Note :**
* If there is any return type other than void then return statement is mandatory.
* For void return statement is not mandatory.

### Recursive Method :
* A method calling itself is called as recursive method.
```
class RecMethod
{
    public static void cat()
    {
        System.out.println("meow...meow...");
        cat();
    }    
    public static void main(String[]args)
    {
        System.out.println("Main Begin");
        cat();
        System.out.println("Main End");
    }
}
```
* __Ans :__ <br>
Main Begin <br>
meow...meow... <br>
    . <br>
    . <br>
    . <br>
infinite loop <br>
    . <br>
stop execution of program

* In above program the cat() method is been called itself is called as recursive invocation.
* It generates an infinite loop for method.
* In order to stop infinite loop we need to pass the base condition.

* __Que1.__ Write a program to print all the even numbers between 0 to 6 using recursive method or without using looping statement.

```
class EvenRec
{
    public static void even(int a)
    {
        if(a == 7)
        {
            return;
        }
        if(a % 2 == 0)
        {
            System.out.println(a);
        }
        even(++a);
    }
    public static void main(String[]args)
    {
        System.out.println("Main Begin");
        even(0);
        System.out.println("Main End");
    }
}
```
* __Ans :__ <br>
Main Begin <br>
0 <br>
2 <br>
4 <br>
6 <br>
Main End

* __Que2.__ Write a program to print product of first five numbers using recursive method. OR Write a program to print factorial of number five using recursive method. 

```
class Product
{
    public static void product(int a, int b)
    {
        if(a == 0)
        {
            System.out.println(b);
            return;
        }
        int pro = b * a;
        product(--a, b = pro);
        
    }
    public static void main(String[]args)
    {
        product(5,1);
    }
}
```
* __Ans :__ 120