#include<stdio.h>
#include<conio.h>
#define MAX 10
/* Define the required functions to create a list, insert into the list, 
delete an element from the list, search and display the list */
void create();
void insert();
void deletion();
void search();
void display();
int a,b[20], n, p, e, f, i, pos;
void main()
{
//clrscr();
int ch;
char g='y';
do
{
printf("\n main Menu");
printf("\n 1.Create \n 2.Delete \n 3.Search \n 4.Insert \n 
5.Display\n 6.Exit \n");
printf("\n Enter your Choice");
scanf("%d", &ch);
/* The following switch will call the appropriate choice provided 
by the user */
switch(ch)
{
case 1:
create();
break;
case 2:
deletion();
break;
case 3:
search();
break;
case 4:
insert();
break;
case 5:
display();
break;
case 6:
exit();

