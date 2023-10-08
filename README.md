# THE_LARGEST_OfThree
finding the largest value out of 3 values 
public class Largest {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int num1,num2,num3,largest;
        
        System.out.print("enter number1");
         num1 =input.nextInt();
         System.out.print("enter number2");
          num2 =input.nextInt();
         System.out.print("enter number3");
         num3=input.nextInt();
         if((num1>num2)&&(num1>num3))
             largest=num1;
             else if (( num2>num3))
                 largest=num2;
                     
                     
             else 
                largest = num3;
         
         System.out.print(largest);
    }
