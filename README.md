public class myprogram 

{

   public static void main(String ar[])
   {
        for (int i=1;i<=5;i++)
		{
		for (int j=1;j<=5;j++)
		{
		
		if (i%2==0)
			
		{
		System.out.print("*");
		
		}
		else
		{ 
		System.out.print("0");
		}
		
		
		}	
		System.out.println(" ");
     }
}
}        


00000 
***** 
00000 
***** 
00000 
------------------------------------------------------


public class myprogram 

{

   public static void main(String ar[])
   {
        for (int i=1;i<6;i++)
		{
		for (int j=1;j<6;j++)
		{
		
		if
		(i==1||i==5||j==1||j==5)
			
		{
		System.out.print("0");
		}
		else
		{ 
		System.out.print("*");
		}
		
		
		}	
		System.out.println(" ");
     }
 }
}        


00000 
0***0 
0***0 
0***0 
00000 

-----------------------------------------------------


public class myprogram 

{

   public static void main(String ar[])
   {
        for (int i=0;i<4;i++)
		{
		for (int j=0;j<5;j++)
		{
		
		if
		(i==j||i+j==4)
			
		{
		System.out.print("0");
		}
		else
		{ 
		System.out.print("1");
		}
		
		
		}	
		System.out.println(" ");
     }
 }
}        


01110 
10101 
11011 
10101 

----------------------------------------------------


public class myprogram 

{

   public static void main(String ar[])
   {
        for (int i=0;i<5;i++)
		{
		for (int j=0;j<5;j++)
		{
		
		if
		(i==2||j==2)
			
		{
		System.out.print("0");
		}
		else
		{ 
		System.out.print("1");
		}
		
		
		}	
		System.out.println(" ");
     }
 }
}        

11011 
11011 
00000 
11011 
11011 
---------------------------------------------------
public class Cricket {
    String name;
    String postion;
    int    number;
static String team="india";//Static variable

void info()

{
    System.out.println("Name :"+name+"Postion :"+postion+"Jersy no :"+number+","+team);
}

 public static void main(String args[]) {
    
    Cricket t1=new Cricket();
    Cricket t2=new Cricket();
    t1.name="kohli";
    t1.postion="right-hand batsman";
    t1.number=18;
 

    t2.name="b.kumar";
    t2.postion="right-arm fast medium bowler";
    t2.number=15;
    t1.info();
  t2.info();
    }
}

Output

Name :kohliPostion :right-hand batsmanJersy no :18,india
Name :b.kumarPostion :right-arm fast medium bowlerJersy no :15,india

























