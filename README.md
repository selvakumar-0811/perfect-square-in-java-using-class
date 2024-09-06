# perfect-square-in-java-using-class
import java.util.*;
class square
{
    int a;
    static void getlawrance(int a)
    {
        int i=1,f=1;
        while(i*i<=a)
        {
            if(i*i==a)
            {
                f=0;
                System.out.print("perfect");
                break;
            }
            i++;
        }
            if(f==1)
                System.out.print("not");
    }
}
public class Main
{
	public static void main(String[] args) 
	{
	    Scanner sc=new Scanner(System.in);
	    int a=sc.nextInt();
	    square.getlawrance(a);
		
	}
}
