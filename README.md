# Practice
For Exam 

package functionoverloading;

 class loading
{
     int a,b;
    void res(int x, int y)
    {
        a=x;
        b=y;
        System.out.println("Summation IS: "+(a+b));
    }
    void res(int x)
    {
        a=x;
        System.out.println("Summation IS: "+(a*a));
    }
    
}

public class FunctionOverloading {

    public static void main(String[] args) {
       
        loading obj=new loading();
        obj.res(10);
        obj.res(1100,200);        
    }
    
}
