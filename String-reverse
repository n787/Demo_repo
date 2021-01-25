#include <stdio.h>
#include<string.h>
#include <stdlib.h>

void find_string_present(char sentence[100],char str[50])
{
       int i,j=0,n1,n2,n;
       int cnt=0;
      // n1=strlen(sentence);
   n2=strlen(str);
n2--;
   for(i=0;str[j]!='\0';i++)
   {
            if(str[j]==sentence[i])
            {
                    n=i-n2;
                    j++;
                    cnt=1;
            }
            else
                    j=0;
   }
      if(cnt==1)
   printf("The string '%s' is present at index %d\n",str,n);
   else
        printf("The string %s is not found ",str);
}
int main()
{
   char sentence[100],str[50];

   printf("Enter the sentence: ");
   gets(sentence);
   printf("Enter the string: ");
   gets(str);
find_string_present(sentence,str);
    return 0;
}
