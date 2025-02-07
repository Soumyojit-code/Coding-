//chech whethr a number is automorphic number or not.
#include <stdio.h>
#include<math.h>
int main()
{
    int Number,count;
    printf("Enter a number: ");
    scanf("%d",&Number);
    int tem =Number;
    int square = pow(Number,2);
    while(Number!=0)
    {

        if(Number % 10 != square % 10)
        {
            count =0;
        }
        else if(Number % 10==square % 10)
        {
            count=1;
        }
        Number=Number/10;
        square=square/10;
    }
    if(count)
        printf("Number : %d is a Automorphic Number",tem);
    else
        printf("Number : %d is not a  Automorphic Number",tem);

    return 0;
}
