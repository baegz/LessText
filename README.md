# LessText
LessText is an interpreter for our custom language .code

It contains

loop for

loop while

do-while loop

If / elif / esle instructions

You can declare primitive types: int, bool, double, string


The grammar of .code is contained in the function procedure, as it is specified in the following example...



start procedure(){

	code.int num=0, cont;
	code.print("Enter a number ");
	code.scan(num);
	
	code.print("calculating if a number is prime");
	cont=0;
	code.for(code.int i = 0; i <= num; i++){
		code.int k = num%i;
		code.if(k == 0){
			cont++;
		}
	}
	code.if(cont == 2){
		code.print("Is prime");
	}code.else{
		code.print("Is not prime");
	}

	code.print("Now we gonna show the firts 100 numbers");
	cont=0;
	code.do{
		cont++;
		code.print("The new value is "+cont);
	}code.while(cont<100);
	
	code.print("End of program");
}


For more information, contact: baegzgham@gmail.com
