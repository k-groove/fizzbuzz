// print fizz, buzz, or fizzbuzz
public class FizzBuzz {
	public static void main(String[]args){
	// the long way	
		for(int i = 1;i < 101; i++){
			if (i % 15 == 0)
				System.out.println("fizzbuzz");
			else
				if(i % 3 != 0 && i % 5 != 0)
					System.out.println(i);
				else
					if(i % 3 == 0)
						System.out.println("fizz");
					else
						if(i % 5 == 0)
							System.out.println("buzz");
		}
		// short answer using if/then else
		for (int i=1; i < 101; i++) {
		    String string = "";
		    string += (i % 3 == 0) ? "fizz" : "";
		    string += (i % 5 == 0) ? "buzz" : "";
		    System.out.println( (string.equals("") ? i : string) );
		}
	}

}
