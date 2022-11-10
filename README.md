*/ Name: Ramil Ibonalo
* Section : Devotion IT dept
* Year: 4th year
*/


import java.util.Scanner;
public class Main {
	public static void main(String[] args) {
		Scanner myInput=new Scanner(System.in);
		int Grade=1;
		int total=0;
		int rep=0;
		
		while(Grade==1){
		    System.out.print("Enter Grade:");
		    int grade=myInput.nextInt();
		    
		    total+=grade;
		    rep+=Grade;
		    
		    System.out.println("Do you want to enter another grade?\[1]YES   [2]NO:");
		    Grade=myInput.nextInt();
		    
		}
		total=total/rep;
		System.out.print("AVERAGE:" + total);
    }	
}
