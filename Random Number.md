# Practice
For Exam 

package random_number;

import java.util.Random;
public class Random_Number {

    public static void main(String[] args) {
        Random dice=new Random();
        int req;
        for(int i=0;i<=10;i++)
        {
           req=1+dice.nextInt(6);
           System.out.println(req +" ");
        }
//        int freque1=1;
//        int freque2=0;
//        int freque3=0;
//        int freque4=0;
//        int req;
//        
//        for(int i=1;i<=500;i++)
//        {
//            req=dice.nextInt(7);
//            switch (req)
//            {
//                case 1:
//                    ++freque1;
//                    break;
//                case 2:
//                    ++freque2;
//                    break;    
//                case 3:
//                    ++freque3;
//                    break;
//                case 4:
//                    ++freque4;
//                    break;
//            }
//        }
//        System.out.println("req\tFrequency");
//        System.out.printf("1\t%d\n2\t%d\n3\t%d\n4\t%d\n" ,freque1,freque2,freque3,freque4);
//        
//  }
}
