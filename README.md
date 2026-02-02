# recurrsive

#include<stdio.h>
void factorial(int n){
if(n==0){
return 1;
}
else{
return fact(n-1)*n;
}
}
int main(){
int n;
printf("enter number:\n);
scanf("%d",&n);
factorial(n);
return 0;
}
