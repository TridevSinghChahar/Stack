#include<stdio.h>
#include<conio.h>
void push();
void pop();
void display();
int stack[5],top=-1;
void push()
{
	int n;
	printf("Enter a number to be push\n");
	scanf("%d",&n);
	if(top==4)
	printf("stack is overflow:\n");
	else
	{
		top=top+1;
		stack[top]=n;
	}

}
void pop()
{
	if (top==-1)
	printf("stack is overflow:\n");
	else
	{
	printf("\n deleted data=%d",stack[top]);
	top=top-1;
	}
}
void display()
{
	int i;
	if (top==-1)
	printf("stack is underflow:\n");
	else
	{
	for(i=top;i>=0;i--)
		{
		printf("%d",stack[i]);
		 }
	}
}

void main()
{
int ch;
char ch1;
do
{
	printf("press 1 for push:\n");
	printf("press 2 for pop:\n");
	printf("press 3 for display:\n");
	printf("press 4 for exit:\n");
	printf("enter your choice:\n");
	scanf("%d",&ch);
	switch (ch)
	{
		case 1: push();
		       break;
		case 2: pop();
		       break;
		case 3: display();
			break;
		case 4: exit(0);
			break;

		default:printf("Invalid Choice");
			break;
	  }

	  printf("do you want to continue\n");
	  fflush(stdin);
	  scanf("%c",&ch1);
}
	while(ch1=='y'||ch1=='y');
	getch();
	}
