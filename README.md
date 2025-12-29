#include <stdio.h>
//thap 7 tang
//chia 2 phan:
//dia to 
//chong dia nho
//di chuyen co ban:
//chong dia nho --> kho
//dia lon --> dich
//chong dia nho --> dich
void thap(int n, char a, char b, char c){
//n(so dia) , a(nguon), b(kho), c(dich)
//neu chi con 1 dia thi chuyen thang qua dich
  if(n == 1){
     printf("di chuyen dia %d %c-->%c "n, a, c);
     return;
  }
  
}
int main(){
  char a = 'A', b = 'B', c= 'C';
  int n;
  printf("Nhap n: ");
  scanf("%d", &n)
  thap(n, a, b, c);
}
