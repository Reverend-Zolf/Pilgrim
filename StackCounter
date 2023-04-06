#include <stdio.h>
#include <stdlib.h>

#define MAX_SIZE 5

int stack[MAX_SIZE];
int top = -1;

int pop() {
    if (top == -1) {
        printf("Error: EMPTY\n");
        exit(1);
    }
    return stack[top--];
}

void push(int x) {
    if (top == MAX_SIZE - 1) {
        printf("Error: FULL\n");
        exit(1);
    }
    stack[++top] = x;
}

int count_elements() {
    int count = 0;
    for (int i = 0; i <= top; i++) {
        count++;
    }
    return count;
}

int main() {
    push(1);
    push(2);
    push(3);
    

    printf("A pilha contem %d elementos\n", count_elements());
    return 0;
}
