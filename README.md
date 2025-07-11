package variables;

class global {
	int b = 45;// global variable
	int  c = 23 ;
		
	
	
	public static void main(String[] args) {
		global g1 = new global();
		System.out.println(g1.b + g1.c);
		System.out.println(g1.b - g1.c);
		System.out.println(g1.b * g1.c);
		System.out.println(g1.b / g1.c);
		System.out.println(g1.b % g1.c);
		
		
	}
} 
