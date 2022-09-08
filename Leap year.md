```c
#include <stdio.h>
#include <conio.h>
void isLeapYear(){
    int Y,c;
    printf("\nEnter a year:-");
    scanf("%d",&Y);
    if(Y%4 == 0){
        printf("This is a leap year!!!\t");
    }
    else{
        printf("This is not a leap year!!!");
    }
    
    
}
int main()
{
    
    char ch='y';
    while (ch=='y' || ch=='Y')
    {
        //clrsr();
        isLeapYear();
        printf("Do you wish to continue(y/n)");
        ch=getch();
    }
    
    return 0;
}

##OUTPUT
Enter a year:-2034
This is not a leap year!!!Do you wish to continue(y/n)
Enter a year:-
3212
This is a leap year!!!  Do you wish to continue(y/n)
```
