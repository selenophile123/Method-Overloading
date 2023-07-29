# Method-Overloadingimport java.util.Scanner;

public class Method {
    public int sum(int a,int b){
        return(a+b);
    }
    public float sum(float a,float b){
        return (a*b);
    }

    public static void main(String[] args) {
        Method m=new Method() ;
        Scanner sc=new Scanner(System.in);
        int a= sc.nextInt();
        int b= sc.nextInt();
        System.out.println("sum of the number:");
        System.out.println( m.sum(a,b));
    }
}

