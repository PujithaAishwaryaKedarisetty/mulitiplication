# mulitiplicationimport java.util.*;
 public class multiplication
{
    public static void main (String[] args){
        
     int n,i,result;
    Scanner s=new Scanner(System.in);
    //System.out.println("enter n value");
    n=s.nextInt();
    for(i=1;i<11;i++) 
    {
        result=i*n;
        System.out.println(+ n + " x " + i + " = " + result);
    }
    }}

