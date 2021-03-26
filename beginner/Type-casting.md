## Type Casting 

<br>

![Dig7](https://raw.githubusercontent.com/sangam14/JavaLabs/master/img/Dig7.png)
* The process of converting one datatype into another datatype is called as type casting.
* Type casting is classified into two types :<br>
  1)Primitive Type Casting 
  2)Non-primitive Tpe Casting 

### 1) Primitive Type Casting 
* The process of converting one primitive datatype into another primitive data type is called as primitive type casting.
* Primitive type casting is classified into two types : <br>
   i] Widening <br>
   ii] Narrowing 

### i] Widening 
* The process of converting smaller datatype into larger data type is called as widening.
* Widening is done by the compiler automatically, hence it is also called auto widening.
* In widening there will be not loss of data.
* In widening we will get addition of data.

```
class P1
{
    public static void main(String[]args)
    {
        char ch = 'a';
        int b = ch;
        System.out.println(ch);
        System.out.println(a);
    }
}
```
* Ans = a, 97

```
class P1
{
    public static void main(String[]args)
    {
        char a = 10;
        float b = a;
        System.out.println(a);
        System.out.println(b);
    }
}
```
* Ans = 10, 10.0

```
class CharToFloat
{
    public static void main(String[]args)
    {
        char ch;
        ch = 'a';
        float f;
        f = ch;
        System.out.println(ch);
        System.out.println(f);
    }
}
```
* Ans = a, 97.0

```
class FloatToDouble
{
    public static void main(String[]args)
    {
        float f1 = 20.5f;
        double d1 = f1;
        System.out.println(f1);
        System.out.println(d1);
    }
}
```
* Ans = 20.5, 20.5
* __Note__ <br>
   In order to identify the float value it should be represented interms of 'f'<br>
   e.g. 10.15f



### ii] Narrowing
* The process of converting larger datatype into  smaller data type is called as narrowing.
  


```
class P3
{
    public static void main(String[]args)
    {
        int n = 97;
        char ch = n; // CTE
        System.out.println(n); 
        System.out.println(ch);
    }
}
```
* Ans = Compile Time Error
<br><br>

* We can not do narrowing automatically.
* In order to perform narrowing we need to take the help of cast operator.
* In narrowing there will loss of the data.
### CAST Operator
* Cast operator is an unary operator.
* It will take only one value/operand at a time.
* Cast operator will help us to convert larger datatype into smaller datatype.
* __Syntax__ <br>
  &nbsp; datatype variable_name = (datatype) variable_name;

```
class P3
{
    public static void main(String[]args)
    {
        int n = 97;
        char ch = (char) n; 
        System.out.println(n); 
        System.out.println(ch);
    }
}
```
* Ans = 97, a

```
class P4
{
    public static void main(String[]args)
    {
        float n = 10.15f;
        int a = (int) n; 
        System.out.println(n); 
        System.out.println(a);
    }
}
```
* Ans = 10.15, 10




