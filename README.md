#include<stdio.h>
#include<string.h>
#include<stdlib.h>
char * myreverse(char * str)
{
    static int i=0;
    static char rev[100];
    if(str[0]!='\0')
    {
       myreverse(str+!)
       rev[i++] = *str;
     }
     return rev;
}
int main()
{
   chat a[100];
   char *b;
   int i=0,k;
   printf("Enter string:\n");
   scanf("%s",a);
   b=myreverse(a);
   printf("\nReversed string :%s",b);
   return 0;
 }  
