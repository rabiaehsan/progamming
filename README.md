#include<stdio.h>
#include<conio.h>
int  main()

{
	int score[7]={10,11,12,13,14,15,16};
	int count=0,sum=0;
	float avg=0;
	int answer[7];
	for(count=0;count<=7;count++)
	{
	sum+=score[count];
	}
 avg=sum/7;
 printf("\n%d",sum);
 printf("\n%f",avg);
 printf("\n");

	for(count=0;count<7;count++)
{
 		answer[7]=(score[count]-avg)*(score[count]-avg);
 		printf("%d \n",answer[7]);
}
	 return 0;	
}
	 	 
