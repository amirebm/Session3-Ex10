# Session3-Ex10

// ب ن ک بزرگترین عدد 3 رفمی که بر سه و پنج بخش پذیر است را در خروجی چاپ کند

package com.personal.ex10;

public class Ex10 {

	public static void main(String[] args) {


		for(int i=999; i >100; i--)
			if((i % 5==0) && (i % 3==0) ) {
				System.out.println("bozorgtarin addade 3 raghami ke bar 3 va 5 "
						+ " bakhsh pazir ast "+ i+ " mibashad" );
			System.exit(i);	
			}
		
	}

}
