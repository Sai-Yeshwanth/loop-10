public class Jala {

	public static void main(String[] args) {
		int n=717,a;
		int sum=0;
		int temp;
		temp=n;
		while(n>0)
		{
			a=n%10;
			n=n/10;
			sum=sum*10+a;
		}
		if(temp==sum)
		{
			System.out.println("Given number is Palindriome");
		}
		else{
			System.out.println("Given number is not Palindriome");
		}
		
	}
}
