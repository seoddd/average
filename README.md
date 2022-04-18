# average
Find the average of numbers
#include <stdio.h>

int main(void) {
  int i,b,sum,aver; // b는 자료 개수
  int a[1000];
  scanf("%d\n",&b);
  for(i = 0;i<b;i++){
    scanf("%d",&a[i]); //배열 입력받기
  }
  for(i = 1; i<b; i++){ //평균구하기
    sum+=a[i];
    aver = sum/b;
  }
  printf("%d",aver);
}
