# DRAWING-BOOK-HACKERRANK
this problem statement was given in problem solving portion of hackerrank
#include <assert.h>
#include <limits.h>
#include <math.h>
#include <stdbool.h>
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
int main()
{
    int n,p,no;
    scanf("%d",&n);
    scanf("%d",&p);
    int d=n-p;
    int k=p-1;
    if((n-p)<=(p-1))
    {
        if(n%2!=0)
        {
            no=d/2;
        }
        else 
        {
        if(p%2==0)
        {
            no=d/2;
        }
        else
        {
            no=(d/2)+1;
        }
        }
    }
    else
    {
        if(p%2!=0)
        {
            no=k/2;
        }
        else
        {
            no=(k/2)+1;
        }
    }
    printf("%d",no);

}
