# Coding-Ninaja-Introduction-to-Patterns
Reverse Number Pattern

import java.util.Scanner;
public class Solution {


	public static void main(String[] args) {
		
		/* Your class should be named Solution.
	 	* Read input as specified in the question.
	 	* Print output as specified in the question.
		*/
         Scanner in = new Scanner(System.in);
        int n = in.nextInt();
       
        for(int i = 1; i <= n; i++){
            for(int j = i; j>=1;j--) {
                System.out.print(j+"");
            } System.out.println();

        }
	}

}
