# java
public class SwapDemo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int fno = 100;
		int sno = 200;
		
		System.out.println("Before Swapping : ");
		System.out.println("Fno : "+ fno + " Sno :" +sno );
		
		//Swapping with temp variable
		int temp=0;
		temp=fno;
		fno=sno;
		sno=temp;
		
		System.out.println("After Swapping : ");
		System.out.println("Fno : "+ fno + " Sno :" +sno );
		
		
		

	}

}
