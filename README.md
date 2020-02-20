# day-twelve
another new day, learning new thing.
trying to solve the question of #codechef.
#forth_question

#include<stdio.h>
#include<conio.h>

void main(){
    int t,s,h,x,sum,,mn;
    scanf("%d",&t);
    while(t-->0){
        scanf("%d",&s);
        scanf("%d",&h);
        scanf("%d",&x);
        if(s<=h)
            mn=s;
        else if(h<=s)
            mn=h; 
            sum=(s+h+x)/3;
        if(sum<=mn)
            sum=mn;
            printf("\n%d\n",sum);
        else
            printf("\n%d\n",sum);
    }
getch();
}
