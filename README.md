# Java-exp-8
# Inheritance
# Aim:
To write a Java program using inheritance one class can acquire the properties of others.

# Algorithm:
Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class called "Animal" and create required statements.

Step 3 : Create a another class called "Bird" and create required statements.

Step 3 : Create another class,called the Solution Class.

Step 4 : Using the 'extends' keyword you can inherit classes, do the same with above created class.

Step 5 : Display the statements from the first and secomd Class using Solution Class in the terminal.

# Program:

<br>class Animal{<br>
void walk(){<br>
System.out.println("I am walking");<br>
  }<br>
}<br>

class Bird extends Animal{<br>
void fly(){<br>
System.out.println("I am flying");<br>
  }<br>
}<br>

public class Solution{<br>
public static void main(String args[]){<br>
Bird bird = new Bird();<br>
bird.walk();<br>
bird.fly();<br>
  }<br>
}<br>
# Output:
![image](https://github.com/Anuayshh/Java-exp-8/assets/127651217/67318820-8903-40e0-8561-e6e608df4c5f)

# Result
We have successfully created a Java program using inheritance one class can acquire the properties of others.
