i) Java Program to Find Largest Element in an Array
class Max {
public static void main(String[] args) {
int a[]={1,2,3,4,5};
int max;
for(int i=0;i<a.length;i++)
{

System.out.println(a[i]);
}

max = a[0];
for(int i = 0; i < a.length; i++)
{
if(max < a[i])
{
max = a[i];
}
}
System.out.println("Maximum value:"+max);
}
}

ii) Java Program to Print Even and Odd Elements in an Array
class EvenOdd {
public static void main(String[] args) {
int a[]={1,2,3,4,5,6,7,8,9,10};
int max;
System.out.println("Even Nos");
for(int i=0;i<a.length;i++)
{
if(a[i]%2==0)
System.out.println(a[i]);
}
System.out.println("Odd Nos");
for(int i=0;i<a.length;i++)
{
if(a[i]%2!=0)
System.out.println(a[i]);
}
}
}
