# Number-guess
import java.util.Scanner;
import javax.swing.plaf.basic.BasicTableHeaderUI;
class Guessinggame
{
    public static void main(String[] args) {
        {
            System.out.println("Start Guess a number game! \n\n");
            System.out.println("Enter your name to start \n");
            Scanner sc =new Scanner(System.in);
            String name = sc.nextLine();


            System.out.println("Hello "+name+"!!! \n");
            System.out.println("Shall we beginn!!!");
            System.out.println("\t 1.Start the quiz");
            System.out.println("\t 2. Quit the quiz");
    
            int option =sc.nextInt();
    
            while(option!=1)
            {
                System.out.println("Shall we beginn!!!");
                System.out.println("\t 1.Start the game");
                System.out.println("\t 2.Quit the game");
                option=sc.nextInt();
            }
            
            System.out.println("Enter a number");
            int Random=(int)(Math.random()*100+1);
            
            int N =sc.nextInt();
            int count=1;
            while(N!=Random)
            {
                count++;
                if(N<Random)
                System.out.println(N+"is Smaller");

                else
                System.out.println(N+ " is Greater \n");
                System.out.println("Enter another number");
                N=sc.nextInt();
            }
            if (count==1) System.out.println("*****\nCongratulations!!!");
            else if(count==2)System.out.println("***\nCongratulations!!!");
            else if(count==3)System.out.println("*\nCongratulations!!!");
            else System.out.println("\nCongratulations!!!");
        }
    }
}
