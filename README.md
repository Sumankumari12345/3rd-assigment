#include <stdio.h>

#include<conio.h>

void main()

{

   int n,i,table;

   clrscr();

   printf("Enter a number you want to print the table:\n");

   scanf("%d",&n);

   clrscr();

   printf("Table of %d :\n",n);

   for(i=1;i<=10;i++)

   {

       table=i*n;

       printf("%d\n",table);

   }

   getch();

}
