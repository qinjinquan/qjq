public class exp2{  
    public static void main(String args[]){  
        int i=0;  
        for(i=1;i<=20;i++)  
            System.out.println(f(i));  
    }  
    public static int f(int x)  
    {  
        if(x==1 || x==2)  
            return 1;  
        else  
            return f(x-1)+f(x-2);  
    }  
}  





public class Ex10 {  
 public static void main(String[] args)  
 {  
     double s=0;  
     double t=100;  
     for(int i=1;i<=10;i++)  
     {  
         s+=t;  
         t=t/2;  
     }  
     System.out.println(s);  
     System.out.println(t);  
       
 }  
}  