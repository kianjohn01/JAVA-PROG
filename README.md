import java.util.Scanner;

public class java{
    public static void main(String [] args){
        Scanner input=new Scanner(System.in);
        double GrossPay;
        double SSS;
        double Tax;
        double PagIbig;
        double TotalDeduction;
        
        
        System.out.print("  Enter Gross Pay:");
        GrossPay = input.nextDouble();
       System.out.println("====================");
        System.out.print(" SSS :");
        
        SSS = input.nextDouble();
        System.out.println("====================");
        System.out.print(" Tax: ");
        
        Tax = input.nextDouble();
        System.out.println("====================");
        System.out.print(" PagIbig:");
      
        PagIbig= input.nextDouble();
        TotalDeduction = SSS + Tax + PagIbig;
        double netpay = GrossPay -TotalDeduction;
        System.out.println("====================");
        System.out.print("Net pay " +netpay);
        
        
    }
    }

