# hello-world
从这里开始编程之路。
#include <stdio.h>
int main()
{
int a, b, c;
scanf("%d%d%d",&a,&b,&c);
if(c==0&&b==0){
 printf("%d",a);
}
else if(c==0){
 printf("%d%d",b,a);
}
else{
 printf("%d%d%d",c,b,a);
}
 return 0;
}
