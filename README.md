# food-items
#include<stdio.h>
#include<conio.h>
main()
{
	int num= 4;
	printf("Enter food code: ");
	scanf("%d",&num);
	
        switch (num) 
		{
            case 1:
                printf("Pizza- Rs-239");
                break;
            case 2:
                printf("Burger- Rs-129");
                break;
            case 3:
                printf("Pasta - Rs-179");
                break;
            default:
                printf("French Fries - Rs-99");
                break;
        }
        return 0;
    
}
