
import java.io.FileNotFoundException;
import java.io.FileReader;
import java.util.Scanner;

public class scanner {

	public static void main (String args[]) throws FileNotFoundException
	{
	int loc=0;
	double kloc;
	Scanner scanner = new Scanner(new FileReader("F:\\eclipse\\Lab\\file\\filename.txt"));
	{
	while(scanner.hasNextLine())
	
		String st = scanner.nextLine();
		loc++;
	}
		System.out.println(loc);
		kloc=loc/1000;
	    System.out.println(kloc);
	    
}
}

