# Login-page
#include<stdio.h>

int main()
{
    int a[3][2];
    int ID, Pin ;
    a[0][0]=12345;
     a[0][1]=56789;
    a[1][0]=43210;
     a[1][1]=87656;
    a[2][0]=20213;
    a[2][1]=20198;
    
    printf("Enter ID: ");
        scanf("%d", &ID);
    printf("Enter PIN CODE: ");
        scanf("%d", &Pin); 
    
    if(ID==a[0][0], Pin==a[0][1])
    {
    printf("You're successfully logged in Sector 1!");
    }else if(ID==a[1][0], Pin==a[1][1])
    {
    
    printf("You're successfully logged in Sector 2!");
    }else if(ID==a[2][0], Pin==a[2][1])
    {
    
    printf("You're successfully logged in Sector 3!");
    }else
    {
    printf("Wrong ID/PIN");
    }
    
    return 0;
}
