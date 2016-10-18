# Noob-Contest-01
here I have given first two solved problems.. there can be more efficient ways.. but these are as per i solved them..

** Back to high school physics **

#include<stdio.h>
int main()
{
    int v,t,c;

    while(scanf("%d%d",&v,&t)==2){
            c=v*2*t;
            printf("%d\n",c);
    }
    return 0;
}



** Hashmat the brave worrior **

#include<stdio.h>
int main()
{
    long long int a,b,c;
    while(scanf("%lld%lld",&a,&b)!= EOF)
    {
        if(a>b){
            c=a-b;
        }
        else{
            c=b-a;
        }
        printf("%lld\n",c);
    }
    return 0;
}
