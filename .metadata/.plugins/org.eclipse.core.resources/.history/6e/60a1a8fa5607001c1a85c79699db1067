import java.util.Scanner; //for input

public class Assignment1 {//class

	public static void main(String[] args) { //Main method
		
		//All variables used throughout code
		String name; //To enter name
		double throw1, throw2, throw3;//Three variables that represent throw distance
		double yards = 1.093;//converts meters to yards
		double feet = 3;//converts meters to feet
		double inches = 12*3;//converts meters to inches
		double centimeters = 100;//converts meters to centimeters
	
		
		Scanner input = new Scanner(System.in);
		
		
		System.out.println("Enter the competitor's name: ");
		name= input.nextLine();//name input
		
		
		System.out.println("Olympic Javelin Throws");
		System.out.println("Enter the distances, in meters, " + name);
		
		System.out.println("Enter the distance of the first throw: ");
		throw1= input.nextDouble();//input first throw in meters
		
		System.out.println("Enter the distance of the second throw: ");
		throw2= input.nextDouble();//input second throw in meters
		
		System.out.println("Enter the distance of the third throw: ");
		throw3= input.nextDouble();//input third throw in meters
		
		//Headings of results
		System.out.printf("%-15s", "Yards");
		System.out.printf("%-15s", "Feet");
		System.out.printf("%-15s", "Inches");
		System.out.printf("%-15s", "Centimeters");
		
		//These are each of the conversions for first throw
		System.out.printf("\n"+ "%-15.2f", throw1*yards);
		System.out.printf("%-15.2f", throw1*feet*yards);
		System.out.printf("%-15.2f", throw1*inches*yards);
		System.out.printf("%-15.2f", throw1*centimeters);
		
		//conversions for second throw
		System.out.printf("\n"+ "%-15.2f", throw2*yards);
		System.out.printf("%-15.2f", throw2*feet*yards);
		System.out.printf("%-15.2f", throw2*inches*yards); 
		System.out.printf("%-15.2f", throw2*centimeters);
		
		//conversions for third throw
		System.out.printf("\n"+ "%-15.2f", throw3*yards);
		System.out.printf("%-15.2f", throw3*feet*yards);
		System.out.printf("%-15.2f", throw3*inches*yards);
		System.out.printf("%-15.2f", throw3*centimeters);
		
		input.close();// closes scanner
	
	}//end main method

	
}//end class
