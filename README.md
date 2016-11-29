
import java.lang.Math;

public class HelloWorld {
	public static int ena(){
		int a = 0;
		int b = arg_b ;
		int c = arg_c ;
		/* 
		Sestej b in c ter rezultat shrani v spremenljivko a	
		-------------------------------------*/
		
		a=b+c;

	  
	  
	  
		//------------------------------------
		return a;
  }
  static int arg_b;
  static int arg_c;
  
  public static boolean dva(){
		int b =  arg_b ;
		boolean a = true;
		/* 
		Preveri ce je b deljiv z 3 in 9.
		Če drži v a shrani true, sicer false
		-------------------------------------*/
	  
	  
	  
	  
	  
		//------------------------------------
		return a;
  }
  public static int tri(){
		int b = arg_b  ;
		int c = arg_c ;
		int a=0;
		
		/* 
		izracunaj b^c, na primer 2^8. Uporabi zanko in rezultat shrani v a;
		-------------------------------------*/
	  
	  
	  
	  
	  
	  
		//------------------------------------
		return a;
  }
  public static int stiri(){
		int a=0;
		/* 
		sestej vsa stevila z vkljucno od -6 do vkljucno 1000 
		rezultat shrani v a
		-------------------------------------*/
	  	
		
		
		
		
		
		
		
		//------------------------------------
		return a;
  }
  public static boolean pet(){
		boolean a=false;
		int b = arg_b;
		int c = arg_c;
		/* 
		preveri ce sta b in c prastevilska dvojcka
		c>b, na primer b=17,c=19
		v a shrani:
		true če je res;
		false če ni;
		-------------------------------------*/
	  
	  
	  
	  
	  
	 
	 
		//------------------------------------
		return a;
	  
  }
  public static void posebna(){
		int b=arg_b;
		int c=arg_c;
		/* 
		zamenjaj vrednosti b-ja in c-ja
		Pravila: ne smeš uporabljati nobene druge spremenljivke
				delovati mora za katerokli pozitivno vrednost b-ja in c-ja
				b in c sta > 0
		-------------------------------------*/
	  
	  	
		
		
		
		
	  
		//------------------------------------
		System.out.println("a: "+(b==arg_c && c == arg_b));
		return;
	  
  }
  
  
  
  public static void main(String[] args) {
    int i=1;
	
	i=printa(i);
	arg_b=5;
	arg_c=20;
	System.out.println("a: "+(ena()==(arg_b+arg_c)));
	i=printa(i);
	arg_b=9999;
	System.out.println("a: "+(dva()==((arg_b%3==0) && arg_b%9==0)));
	arg_b=555;
	System.out.println("   b: "+(dva()==((arg_b%3==0) && arg_b%9==0)));
	arg_b=8;
	System.out.println("   c: "+(dva()==((arg_b%3==0) && arg_b%9==0)));
	i=printa(i);
	arg_b=2;
	arg_c=8;
	System.out.println("a: "+(tri()==(int)Math.pow((double)arg_b,(double)arg_c)));
	arg_b=3;
	arg_c=5;
	System.out.println("   b: "+(tri()==(int)Math.pow((double)arg_b,(double)arg_c)));
	i=printa(i);
	System.out.println("a: "+(stiri()==500479));
	i=printa(i);
	arg_b=17;
	arg_c=19;
	System.out.println(pet()==true);
	i=printa(i);
	arg_b=5;
	arg_c=8;
	posebna();
	
	
  }
  public static int printa(int i){
	  System.out.print(i+": " );
	  return i+1;
  }
}
