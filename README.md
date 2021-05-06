class trailing {
    static long calc(long n){
        int c=0;
        while(n%10==0){
            c++;
            n=n/10;
            
        }
        return c;
        
    }
}
public class Main
{
	public static void main(String[] args) {
		int n=4;
		long fact=1;
		for(int i=n;i>=1;i--)
		{
		    fact=fact*i;
		    
		}
		System.out.println(fact);
		trailing obj=new trailing();
		System.out.println(obj.calc(fact));
		
		
	}
}
