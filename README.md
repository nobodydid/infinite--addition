# infinite--addition
#include <stdio.h>
int main()
{
    int a, b, c, d, e;
    char str[50];
    printf("enter first two numbers\n");
    scanf("%d%d", &a, &b);
    c = a + b;
    printf("your answer is %d\n", c);
    printf("do you wann continue: yes or no\n");
    scanf(" %s", &str);
    while (str == 'y')
    {
        printf("enter ypur new number\n");
        scanf("%d", &d);
        d = c + d;
    }

    return 0;
}
