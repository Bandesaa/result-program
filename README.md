# result-program
c-6
#include<stdio.h>
int main(){
    int a=10,b=5,result;
    printf("Bit-wise operators with a=10 & b=15 \n");
    result = a&b;
    printf("a&b :%d \n",result);
    result = a|b;
    printf("a|b ; %d \n",result);
    result= a^b;
    printf("a^b ;%d \n",result);
    result =~a;
    printf("~a : %d \n",result);
    return 0;
}
