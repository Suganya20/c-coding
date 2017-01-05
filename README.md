#include<stdio.h>
#include<conio.h>
void main()
{
  int n,t;
  scanf("%d",&n);
  if(n>0)
  {
    t=(n%100);
    printf("Positive");
  }
  elseif(n==0)
  {
    printf("Zero");
  }
  else
    printf("Negative");
  getch();
}
