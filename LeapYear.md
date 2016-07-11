**Q1** Write a java equation that prints out the next 20 leap years.

**Solution**

    public class LeapYear {

        public static void main(String[] args) {
        
        int leap=2016;
        
        for (int i = 0; i <= 20; i++){ // print the next twenty leap years
            System.out.print(leap +"\n");
            leap = leap + 4; //every fourth year is leap
            
        }// loop ends
        int i = 0;
        }
    }    
