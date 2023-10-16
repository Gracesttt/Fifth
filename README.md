# Fifth
count3 and reverse number

#include <stdio.h>
int main()
{
    int x;
    printf("Enter the number:");
    scanf("%d",&x);
    
    int i,a;
    int count;
    count=0;
    
    while(x>0){
        if(x%10==3) count++;
        x/=10;
    }
    
    printf("There are %d 3's in this number\n",count);
    return 0;
}


#include <stdio.h>
int main()
//find backward of the number
{
    int num;
    printf("Enter the number:");
    scanf("%d",&num);
    
    
    int a;
    while(num>0){
        a=num%10;
        printf("%d",a);
        num/=10;
        
    }

    return 0;
}


  
