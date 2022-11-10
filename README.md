# Лабораторна робота 3.2

**Дані дійсні (тип Real) числа $х_{11 1}$ , х 2 , х 3 , х та y. Обчислити $F(x)$, якщо**

![alt text](image.jpg)

### Код програми

```c
#include <stdio.h>
int main(void) {
   int x, y, F;
    printf("chuslo \n");
    scanf ("%d%d", &x,&y);
    if (x-y)
    {
        F = (x - y);
    }
    else
    {
        if(x=y)
       
        {
            F = (2*x+(y/2));
        }
        else
        {
            if(x>2)
            {
                F = (y-x+1);
            }
        }
    }
    printf("%d", F);
  return 0;
}
```
### Результат

```console
 make -s
 ./main
chuslo 
3
5
-2 
```
