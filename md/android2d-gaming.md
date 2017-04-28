#Introduction to Android Studio 2D Games

-
-
#What are we going to build

<img src="img/android2D-gaming/ninja_splash.png" height="600" width="700">

-
#What Do We Need to Build it

<img src="img/android2D-gaming/androidstudio.png" height="100" width="100">
<br>
An IDE: Android Studio
<br>
<br>
<img src="img/android2D-gaming/java.png" height="100" width="100">
<br>
A Programming Language: Java
-
-
# What is an IDE?
<p class="fragment fade-up">Integrated Development Environment</p>
<p class="fragment fade-up">An IDE is a software application used for code development and normally consists of:</p>
<p class="fragment fade-up"> a source code editor</p>
<p class="fragment fade-up"> compiler/interpreter</p>
<p class="fragment fade-up"> debugger</p>
-
#What is Java?
<p class="fragment fade-up">Java is a programming language computing platform first released by Sun Microsystems in 1995.</p>
<br>
<p class="fragment fade-up"> In java EVERYTHING is an object</p>
-
-
#Objects

An entity that has a state and behavior
<br>
<br>
Identity: unique identifier for object
<br>
State: data of the objects
<br>
Behavior: the functionality of the object
-
#Person Object
<p class="fragment fade-up">What are some states of a person?</p>
<p class="fragment fade-up">What are some behaviors of a person?</p>
-
-
#Variables and Data Types
variable: A piece of memory that can contain a data value
<br>
<br>
Data Type: Specifies the size and type of value that can be stored in an identifier(variable)
-
#Primative Data Types
![](img/android2D-gaming/dataTypesJava.png)
-
-
#Person Class in Java

```Java
public class Person{
  String name;
  int age;
  double heightInches;
  boolean awake;
}  
```
Class: A template for creating objects
-
-
#Person Class: Statements
<div class="fragment fade-up">
```Java
name = john;
age = 18;
double heightInches = 72;
```
</div>
Statement: a complete unit of execution
-
-
#Person Class: Methods

```Java
public class Person{
  String name;
  int age;
  double heightInches;
  boolean awake;

  public Person(String name, int age, double heightInches, boolean awake){
    this.name = name;
    this.age = age;
    this.heightInches = heightInches;
    this.awake = awake;
  }

  public void speak(){
    System.out.println("Hello");
  }

  public void setAge(int i){
    this.age = i;
  }

  public int getAge(){
    return this.age;
  }
}  
```
-
#Making People Objects from Person Class
```Java
public class People{

  public static void main(String[] args){
    Person john  = new Person(john, 20, 72, true);

    john.speak();
    john.setAge(21);
    System.out.println(john.getAge());
  }
}
```
-
-
#Conditional Logic
If-Else Loop
```Java
if (john.getAge() < 25 ) {
  System.out.println("You cannot rent a car.");
}else{
  System.out.println("You can rent a car.");
}
```
<br>
While Loop
```Java
while( john.getAge() < 25){
  System.out.println("You cannot rent a car.")
}
```
-
-
#Let's Practice 
