//Programs on Classes: String and Math.

//i)Program on Function Overloading
public class Sum {
// Overloaded sum(). This sum takes two int parameters
public int sum(int x, int y)
{
return (x + y);
}
// Overloaded sum(). This sum takes three int parameters
public int sum(int x, int y, int z)
{
return (x + y + z);
}
// Overloaded sum(). This sum takes two double parameters
public double sum(double x, double y)
{
return (x + y);
}
// Driver code
public static void main(String args[])
{
Sum s = new Sum();
System.out.println(s.sum(10, 20));
System.out.println(s.sum(10, 20, 30));
System.out.println(s.sum(10.5, 20.5));
}
}

//ii) Program on constructor

class Student{
int id;
String name;
//creating a parameterized constructor
Student4(int i,String n)
{
id = i;
name = n;
}
//method to display the values
void display()
{
System.out.println(id+" "+name);
}
public static void main(String args[]){
//creating objects and passing values
Student s1 = new Student(111,"Karan");
Student s2 = new Student(222,"Aryan");
//calling method to display the values of object
s1.display();
s2.display();
}
}
