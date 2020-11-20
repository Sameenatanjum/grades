# grades
c program to find grades based on marks

int main()
{
	int a;
	printf("Enter your marks:\n");
	scanf("%d",&a);
	if(a>100)
	printf("invalid marks!!!\nplease enter appropriate marks (0-100).....\n");
	else if((a>=85)&&(a<=100))
	printf( "Your grade is A");
	else if((a>=70)&&(a<=84))
	printf("Your grade is B");
    else if((a>=55)&&(a<=69))
   	printf("Your grade is C");
    else if(a>=40&& a<=54)
   	printf("Your grade is D");
    else
   	printf("Your grade is F");
   	return 0;
}
