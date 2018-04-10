# Zadacha1
Да се напише програма, която на първия ред приема цяло число Н, 
което е големина на масив и после Н на брой числа, в масива. 
Четните да се приравнят на 0
Masiv, chislo N, chetnite=0
import java.util.Scanner;

public class Masiv 
{

	public static void main(String[] args) 
	{
		// TODO Auto-generated method stub
Scanner in = new Scanner(System.in);
System.out.println("Write N");
int n=in.nextInt();
int[] numbers = new int [n];
for(int i = 0; i < numbers.length; i++)
{
numbers [i] = in.nextInt();
if(numbers [i]%2==0)
	numbers [i]=0;

	}
for(int i = 0; i < numbers.length; i++)
{
	System.out.print(numbers[i]+" ");
}
}
}
