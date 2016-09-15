# aFo_-
#include <iostream>
#include <stdio.h>
#include <locale>
#include <math.h>
using namespace std;
 
void tri(unsigned short n);
 
main()
{
    unsigned short n;
    scanf("%u", &n);//ввести с клавиатуры число
    tri(n);
   return 0;
}
 
void tri(unsigned short n)
{
        for(short i=n/2+1 ; i<=n; i++)
      {
        for(short j=0; j<=i; j++)
            if(j<n-i+1) printf("%c", ' ');
                else printf("%c", '*');//выводить *
         puts(""); //выводит передаваемый ей аргумент на экран
      }
}


