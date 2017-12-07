import java.io.*;
import java.util.Random;

public class arrays1{
	public static void main (String []args)throws IOException{
		BufferedReader input=new BufferedReader(new InputStreamReader(System.in));

int i1=0; //array c
int i2=0; // array myarray
int n; //random num
int x=0;  //c array values
int foundcounter=0; //match counter

int c[] = new int[6];             //arrays
int myarray[]= {4,10,24,30,37,46};

Random r = new Random();

	while(i1 < c.length){

		n = r.nextInt(49)+1;
		c[i1] = n;
		i1++;
		System.out.println (c[x]);
		x++;

	}


	System.out.println();

			for (i1=0; i1 < 6; i1++){

						for (i2=0; i2 < 6; i2++){
								if (c[i1] == myarray[i2]){
								System.out.println("Number " + c[i1] + " matched!");
								foundcounter++;
								}

						}
			}
										if (foundcounter==0){
													System.out.println("No matches.");

			}
	}
}
