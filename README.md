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
		
	}

}
