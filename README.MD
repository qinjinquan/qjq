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







public class Wanshu {  
 public static void main(String[] args)  
 {  
     int s;  
     for(int i=1;i<=1000;i++)  
     {  
         s=0;  
         for(int j=1;j<i;j++)  
             if(i % j==0)  
                 s=s+j;  
            if(s==i)  
                System.out.print(i+" ");  
     }  
     System.out.println();  
 }  
}  