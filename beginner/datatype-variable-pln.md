## Datatypes
* Data types are the types of values used in java program.
* Datatypes are classified into two types
  1) Primitive Datatype
  2) Non-primitive Datatype   
### 1) Primitive Datatype
* Primitive data type are the type of primitive values used in java program.
* Primitive data type are classified into

| Type      | Data types | Size   |
|-----------|:----------:|--------|
|  Integer  |    byte    | 1 byte |
|           |    short   | 2 byte |
|           |     int    | 4 byte |
|           |    long    | 8 byte |
|           |            |        |
|  Float    |    float   | 4 byte |
|           |   double   | 8 byte |
|           |            |        |
|  Character|    char    | 2 byte |
|           |            |        |
|  Boolean  |    true    | 1 bit  |
|           |    false   | 1 bit  |
|           |            |        |

* __Note__ <br>
  All are keywords.
### 2) Non-primitive Datatype
* Non-primitive data type are the type of non-primitive values used in java program.
* e.g. String

## Variables
* Variables is the name given to the block of memory to stored the value.
* **Syntax** <br>
  &nbsp; datatype variable_name = value; <br>
  ```
   e.g. int num = 10;   
  ```
* variables are classified into two types :
  1) Global Variables
  2) Local Variables <br>
   
### 1) Global Variables 
* The variables which are declared inside class block such a variables are called as global variables.
* All global variables will having it's default value.

### 2) Local Variables
* The variables which are declared inside the method block such a variables are called as local variables.
* All local variables will not having it's default value. 

![Dig6](https://raw.githubusercontent.com/sangam14/JavaLabs/master/img/Dig6.png)

```
class P1
{
  public static void main(String[]args)
  {
    int var = 10;
    System.out.println(var);
  }
}
```
* Ans = 10
  
```
class P1
{
  public static void main(String[]args)
  {
    int var;
    System.out.println(var);
  }
}
```
* Ans = (Compile Time Error) variable not initillized

```
class P1
{
  public static void main(String[]args)
  {
    int var;
    var = 10;
    System.out.println(var);
  }
}
```
* Ans = 10

```
class P1
{
  public static void main(String[]args)
  {
    int a,b,c;
    a = 10; b = 20; c = 30;
    System.out.println(a);
    System.out.println(b);
    System.out.println(c);
  }
}
```
* Ans = 10,20,30

## Priniting Statements in java

|    | System.out.println()                                                  | System.out.print()                                                                 |
|----|-----------------------------------------------------------------------|------------------------------------------------------------------------------------|
| 1) | Here it will print the statements and curser moves  to the next line. | Here it will print the statement and curser moves  to the next immediate word.     |
| 2)  | We can use println() without passing any value.                       | We can not use print() without passing any value. It will show compile time error. |


