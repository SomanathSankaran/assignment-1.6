# assignment-1.6

QN 1. java code with the class named ‘acad’ and a method ‘main’. Hardcode the program
with two integers and print the sum of those two.

public class acad{
public static void main(String[] args)
{
int a=10;
int b=20;
int sum=a+b;
system.out.println(sum);
}}
 
 Q2. java code with the class named ‘acad’ and a method ‘main’ where, inputs are provided by the user at runtime and the output
is printed.

public class acad{
public static void main(String[] args)
{
Scanner in=new Scanner(System.in);
system.out.println("Enter the Numbers");
int a=in.nextInt();
int b=in.nextInt();
int sum=a+b;
system.out.println(sum);
}}


Q3) Write a program with method name sum() that accepts two parameters from user and print sum of two numbers

public class acad{
public static void main(String[] args)
{

acad o=new acad;
o.sum();
}
void sum ()
{
Scanner in=new Scanner(System.in);
system.out.println("Enter the Numbers");
int a=in.nextInt();
int b=in.nextInt();
int sum=a+b;
system.out.println(sum);
}
}
}
