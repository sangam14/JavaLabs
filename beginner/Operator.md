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
* Ans = 29, 36, 24, 8, 8, 7 <br>



