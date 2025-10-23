# Module-4 Day-3 SEB
## AIM:
To convert the string 'PEACOCK' into lowercase.

## For example:
<img width="306" height="73" alt="image" src="https://github.com/user-attachments/assets/11b881e6-a3f9-4bd3-8461-cbc4051274e6" />

## Program:
```c
#include <stdio.h>
#include <string.h>
#include<ctype.h>
int main()
{
  char str[30];
  
  scanf("%[^\n]", str);
  int i = 0;
  //convert capital letter string to small letter string
  while (str[i] != '\0')
  {
    if (str[i] > 64 && str[i] < 91){ //or if(str[i]>='A' && str[i]<='Z')
      str[i] =tolower(str[i]) ;
    }
    i++;
  }
  printf("Lower case String is:%s", str);
  return 0;
}
```
## Result:
<img width="657" height="117" alt="image" src="https://github.com/user-attachments/assets/52dfacde-97f7-446b-be73-8b7606637292" />
