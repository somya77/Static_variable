# Static_variable
Initialization of static variable
class Test
{
 static int a;
 void disp()
{
 System.out.println("The value is:"+a);
}
public static void main(String args[])
{
 Test obj=new Test();

 Test obj1=new Test();
  obj.a=10;
  obj1.a=20;
obj.disp();
obj1.disp();
}
}
