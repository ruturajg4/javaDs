i) Java program to find whether the given no. is positive or negative.
public class CheckPositiveOrNegativeExample1
{
public static void main(String[] args)
{
//number to be check
int num=912;
//checks the number is greater than 0 or not
if(num>0)
{
System.out.println("The number is positive.");
}
//checks the number is less than 0 or not
else if(num<0)
{
System.out.println("The number is negative.");
}
//executes when the above two conditions return false
else
{
System.out.println("The number is zero.");
}
}
}

ii) Java Program to print weekdays according to integers from 1 to 7.
import java.util.Scanner;
public class Main {

public static void main(String[] args)
{
Scanner in = new Scanner(System.in);
System.out.print("Input number: ");
int day = in.nextInt();
System.out.println(getDayName(day));
}
// Get the name for the Week
public static String getDayName(int day) {
String dayName = "";
switch (day) {
case 1: dayName = "Monday"; break;
case 2: dayName = "Tuesday"; break;
case 3: dayName = "Wednesday"; break;
case 4: dayName = "Thursday"; break;
case 5: dayName = "Friday"; break;
case 6: dayName = "Saturday"; break;
case 7: dayName = "Sunday"; break;
default:dayName = "Invalid day range";
}
return dayName;
}
}
