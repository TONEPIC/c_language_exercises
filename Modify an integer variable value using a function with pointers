#include <stdio.h>
void addThree(int *);
int main() {
    //! showMemory(start=65520)
    int a = 5;
    addThree(&a);
    printf("inside main, value of a: %d\n",a);
    return 0;
}
void addThree(int * a){
    *a = *a + 3;
    printf("inside addThree, value of a: %d\n",*a);
}
