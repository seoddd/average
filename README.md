# average
Find the average of numbers


#include <stdio.h>

int main(void) {
  int i,b,sum,aver;
  int a[1000];
  scanf("%d\n",&b);
  for(i = 0;i<b;i++){
    scanf("%d",&a[i]);
  }
  for(i = 1; i<b; i++){
    sum+=a[i];
    aver = sum/b;
  }
  printf("%d",aver);
}
