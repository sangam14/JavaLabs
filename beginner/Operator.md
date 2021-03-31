## Operators In Java
* Operators are classified into three types :
1) Unary Operator
2) Binary Operator
3) Ternary Operator 

### 1) Unary Operator
* The operator which takes one value/operand at a time is called as unary operator.
* e.g. Increment Operator <br>
  &nbsp; Decrement Operator <br>
  &nbsp; Cast Operator

### 2) Binary Operator
* The operator which takes two values/operands at a time is called as binary operator.
* e.g. Increment Operator <br>
  &nbsp; Logical Operator <br>
  &nbsp; Arithmatic Operator <br>
  &nbsp; Relational Operator 

### 3) Ternary Operator
* The operator which takes three values/operands at a time is called as ternary operator.
* e.g. Conditional Operator <br><br>
### 1)  Unary Operator
### i) Increment Operator
   * Increment operator is classified into two types a) Post Increment  b) Pre Increment <br>
### a)Post Increment Operator
   * The operator which is suffix to it's variable is called as post increment operator.
   * __Syntax__ <br>
   &nbsp; variable_name ++ 

```
class PostInc
{
    public static void main(String[]args)
    {
        int a = 10;
        System.out.println(a);
        System.out.println(a++);
        System.out.println(a);
    }
}
```
* Ans = 10, 10, 11
* __Steps to perform post increment operator__ <br>
i] Use the value present inside the variable.<br>
ii] Increment the value by '1' and update.

```
class PostInc
{
    public static void main(String[]args)
    {
        int a = 10;
        int b = a++;
        int c = b++;
        System.out.println(a++);
        System.out.println(b++);
        System.out.println(c++);
        System.out.println(a);
        System.out.println(b);
        System.out.println(c);
    }
}
```
* Ans = 11, 11, 10, 12, 12, 11

### b)Pre Increment Operator
   * The operator which is prefix to it's variable is called as pre increment operator.
   * __Syntax__ <br>
   &nbsp; ++variable_name 

```
class PreInc
{
    public static void main(String[]args)
    {
        int a = 10;
        System.out.println(a);
        System.out.println(++a);
        System.out.println(a);
    }
}
```
* Ans = 10, 11, 11
* __Steps to perform pre increment operator__ <br>
i] Increment the value by '1' and update. <br>
ii] Use the value present inside the variable.

```
class PreInc
{
    public static void main(String[]args)
    {
        int a = 10;
        int b = 10;
        int c = 10;
        System.out.println(++a + b++ + c++);
        System.out.println(c + a++ + b++ + c++);
        System.out.println(a + b + c++);
        System.out.println(++a + c + b++)
        System.out.println(a);
        System.out.println(b);
        System.out.println(c);
    }
}
```
* Ans = 31, 44, 36, 38, 13, 13, 13

   
### ii) Decrement Operator
   * Increment operator is classified into two types a) Post Decrement  b) Pre Decrement <br>
### a)Post Decrement Operator
   * The operator which is suffix to it's variable is called as post increment operator.
   * __Syntax__ <br>
   &nbsp; variable_name ++ 

```
class PostDec
{
    public static void main(String[]args)
    {
        int a = 10;
        System.out.println(a);
        System.out.println(a--);
        System.out.println(a);
    }
}
```
* Ans = 10, 10, 9
* __Steps to perform post increment operator__ <br>
i] Use the value present inside the variable.<br>
ii] Decrement the value by '1' and update.

```
class PostDec
{
    public static void main(String[]args)
    {
        int a = 10;
        int b = a--;
        int c = b--;
        System.out.println(a--);
        System.out.println(b--);
        System.out.println(c--);
        System.out.println(a);
        System.out.println(b);
        System.out.println(c);
    }
}
```
* Ans = 9, 9, 10, 8, 8, 9

### b)Pre Decrement Operator
   * The operator which is prefix to it's variable is called as pre increment operator.
   * __Syntax__ <br>
   &nbsp; --variable_name 

```
class PreDec
{
    public static void main(String[]args)
    {
        int a = 10;
        System.out.println(a);
        System.out.println(--a);
        System.out.println(a);
    }
}
```
* Ans = 10, 9, 9
* __Steps to perform pre decrement operator__ <br>
i] Increment the value by '1' and update. <br>
ii] Use the value present inside the variable.

```
class PreDec
{
    public static void main(String[]args)
    {
        int a = 10;
        int b = 10;
        int c = 10;
        System.out.println(--a + b-- + c--);
        System.out.println(c + a-- + b-- + c--);
        System.out.println(a + b + c--);
        System.out.println(a);
        System.out.println(b);
        System.out.println(c);
    }
}
```
* Ans = 29, 36, 24, 8, 8, 7 <br><br>

### 2)  Binary Operator
### i) Arithmatic Operator
* It is an binary operator.
* It will takes two values/operand at a time.

```
class P1
{
    public static void main(String[] args)
    {
        int a = 10;
        int c = 10;
        System.out.println(a + c);
        System.out.println(a - c);
        System.out.println(a * c);
        System.out.println(a / c);
        System.out.println(a % c);
    }
}
```
* Ans = 20, 0, 100, 1, 0

* __For Modulos (%)__
* m = 6, n = 7 <br> <br>
* if m < n <br>
  m % n  = m <br>
  e.g. 6 % 7 = 6  <br> <br>

* if m = n <br>
  m % n  = m <br>
  e.g. 7 % 7 = 0  <br> <br>

* if m > n <br>
  m % n  = reminder <br>
  e.g. 8 % 7 = 1  <br> <br>

### ii) Relational Operator
* It is an binary operator.
* The return type of relational operator is in terms of boolean condition.
* (true/false)

```
class P1
{
    public static void main(String[] args)
    {
        int a = 10;
        int b = 20;
        System.out.println(a == b);
        System.out.println(a != b);
        System.out.println(a < b);
        System.out.println(a > b);
        System.out.println(a <= b);
        System.out.println(a >= b);
    }
}
```
* Ans = false, true, true, false, true, false

### iii) Logical Operator
* It is an binary operator.
### a) AND Operator (&&)

| Statement1 | Statement2 | Output |
|:----------:|:----------:|:------:|
|    TRUE    |    TRUE    |  TRUE  |
|    TRUE    |    FALSE   |  FALSE |
|    FALSE   |    TRUE    |  FALSE |
|    FALSE   |    FALSE   |  FALSE |

### b) OR Operator (||)

| Statement1 | Statement2 | Output |
|:----------:|:----------:|:------:|
|    TRUE    |    TRUE    |  TRUE  |
|    TRUE    |    FALSE   |  TRUE  |
|    FALSE   |    TRUE    |  TRUE  |
|    FALSE   |    FALSE   |  FALSE |

### c) NOT Operator (!)

```
class NotOperator
{
    public static void main(String[]args)
    {
        System.out.println(!true);
    }
}
```
* Ans = false
* NOT is an unary operator but it comes under logical operator.

### d) Assignment Operator 
* Assignment operators are used to assigning value to a variable. The left side operand of the assignment operator is a variable and right side operand of the assignment operator is a value.

```
class AssignOp
{
    public static void main(String[]args)
    {
        int a;
        int b;
        a = b = 10;
        System.out.println(a);
        System.out.println(b);
    }
}
```
* Ans = 10, 10
### 2) Ternary Operator
### i) Conditional Operator
* It is an ternary operator.
* It takes three values at a time.
* It is the type of decision making statement in java.

* __Syntax__ <br>
&nbsp; conditon ? statement1 : statement2 <br>
&nbsp; if condition is true then executes the statement1 <br>
&nbsp; if condition is false then executes the statement2 <br>

```
class TerOp
{
    public static void main(String[]args)
    {
        System.out.println(false ? 10 : 20);
    }
}
```
* Ans = 20

```
class TerOp
{
    public static void main(String[]args)
    {
        int a = 10;
        int b = 20;
        int res = a > b ? a : b;
        System.out.println(res);
    }
}
```
* Ans = 20
* __Que.__ Write a program to find the maximum of four numbers using conditional operator.
  
```
class FindMax
{
    public static void main(String[]args)
    {
        int a = 70;
        int b = 90;
        int c = 30;
        int d = 40;
        int res = a > b && a > c && a > d ? a : b > c && b > d ? b : c > d ? c : d;
        System.out.println(res);
    }
}
```
* Ans = 90

* __Que.__ Write a program to find the minimum of four numbers using conditional operator.

```
class FindMin
{
    public static void main(String[]args)
    {
        int a = 11;
        int b = 29;
        int c = 30;
        int d = 41;
        int res = a < b && a < c && a < d ? a : b < c && b < d ? b : c < d ? c : d;
        System.out.println(res);
    }
}
```
* Ans = 11
