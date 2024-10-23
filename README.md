//prime number 
#include<stdio.h>
#include<conio.h>
void main() {
     int n, count = 0;
     clrscr();
     for(int i=1; i <= n; i++) {
          for(int j=2; j <= n; j++) {
                 if(i % j == 0) {
                     count++;
                   }
           }
           if(count == 1) {
               printf("%d,", i);
            }
            count= 0;
    }
    getch();
}
