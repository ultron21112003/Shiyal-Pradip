/*hello everyone My Name Is Shiyal Pradip
In this day i am send This code

Q:- how to find simple interest 
Ans:-
CODE:-*/
// Program To Find Simple Interest
#include<stdio.h>
#include<conio.h>
void main()
{
	long P,N;
	float R,Si;
  clrscr();
	printf("\t\t\t\tFind Simple Interest\n");
	for(P=1; P<=80; P++) printf("*");
	printf("Enter Amount:- ");
	scanf("%ld",&P);
	printf("Enter The Rate of Interest:- ");
	scanf("%f",&R);
	printf("Enter The Time:- ");
	scanf("%ld",&N);
	Si = ( P * R * N ) / 100;
	printf("\nThe Simple Interest is= %f",Si);
  getch();
}
