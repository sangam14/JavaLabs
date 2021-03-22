## Steps to execute a java Program
step 1) Create a source code <br>
step 2) Compile the source code <br>
step 3) Execute the byte code <br>
### Step 1) Create a source code 
* To create a source code we need take the help of an editor.
* An editor is a software which help to write a java program.
* for e.g. notepad,notepad++,edit+ etc.
* There are some advance editors like IDE,eclipse, atom etc.
  
### Step 2) Compile a source code
* In order to compile the source code we need to install the software called JDK (Java development Kit) 
* By installing the JDK it will install the java compiler (Javac)
* With the help of java compiler we can compile the source code.
* During compiling it will check for the two type of errors
  1) Systax error
  2) Symmetric error
* During compiling if there is any error it will not generate the byte code.
* Only when the source code is error free only then it will generate the byte code.

### Step 2) Execute the byte code
* We can execute the java byte code with the help of command promt.

## Structure of java program
![Dig5](https://raw.githubusercontent.com/sangam14/JavaLabs/master/img/Dig5.png)

```
class FirstProgram
{
  public static void main(String[]args)
  {
    System.out.println("Hello World");
  }
}
```
* Save the java code using .java extension
```
 FirstProgram.java
```
* We need to compile the java source code with the help of java compiler using command promt. 
```
 javac FirstProgram.java
```
* Compiler will generate the byte code. To execute the byte code 
```
 java FirstProgram
```
