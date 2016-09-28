# 09-28-16-switch
import java.util.*;
public class Switch {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner k=new Scanner(System.in);
      	int num=0;
      	char gender=' ';
      	char letter=' ';
        String state="";
        
    
      		System.out.println("Enter F or M");
      			gender=k.next().toUpperCase().charAt(0);
      		System.out.println("Enter a letter");
      			letter=k.next().toUpperCase().charAt(0);
      	    System.out.println("Enter two letter state");
      			state=k.next().toUpperCase();
      			switch (state) {
				case "AL":System.out.println("Alabama");break;
				case "MI": System.out.println("Michigan");break;
			

				default:System.out.println("Invalid state");
					break;
				}
      			
     
      		System.out.println("Enter an integer");
      			num=k.nextInt();
      			switch (num/10) {
				case 0:System.out.println(num);break;

				default: System.out.println((char)(num+55));
					break;
				}
      if (num>=0&&num<99)
      {
    	  switch (num/10) 
    	  {
    	  case 9 :System.out.println("A");break;
    	  case 8:System.out.println("B");break;
    	  case 7:System.out.println("C");break;
    	  case 6:System.out.println("D");break;

    default:
  		System.out.println("F");
  		break;
  	}}
      else
      {
    	  System.out.println("Invalid grade=0-99");
      }
      switch (letter) {
	case 'A':case'E':case'I':case'O':case'U': 
		System.out.println("it is a vowel");break;
	case'Y':
	System.out.println("Sometimes");
	
		break;

	default:
		System.out.println("it is consonant");
		break;
	}
      switch (gender){
	case 'F':System.out.println("Female");break;
	case 'M':System.out.println("Male");break;
	

	default:System.out.println("both or invalid");
		break;
	}
      switch (num%2) {
	case 0 :
		System.out.println("it is even");
		break;

	default:
		System.out.println("it is odd");
		break;
	}
	}

}
