    #include <stdio.h>

    int main() {

    for (int i = 1; i <= 10; i++) {
        if (i % 5 == 0) {
            printf("이것이 저의 최선입니다...\n");
        } else {
            printf("%d\n", i);
        }
    }

    return 0;
    }
