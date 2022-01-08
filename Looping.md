# Programming
// Printing Alphabets in Small and Big Letter Patter like this: a B c D e F g H i J k L m N o P q R s T u V w X y Z

public class AplhLetters{  
public static void main(String args[]){  
    char SLet;
    char BLet;  
    
    System.out.println("Aphabets In Small And Big Letter Pattern");  
    // Responsible for Small Letters
    for(SLet = 'a'; SLet < 'z'; SLet++){  
        while(SLet%2!=0)
        {  
            System.out.print(SLet+ " ");
            SLet++;}
        }

    System.out.println();
    // Responsible for Big Letters
    for(BLet = 'A'; BLet < 'Z'; BLet++){  
        while(BLet%2!=1)
        {  
            System.out.print(BLet+ " ");
            BLet++;}
        }
        
    // Combination of Small and Big Letter    
    // No idea how to combine them
    }
}  
