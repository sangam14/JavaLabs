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
* We can return two datatype of values. <br>
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



