Практична робота №4 Мануйленко Микола

    #include <stdio.h>

    int main() {
    int number, divisor_count = 0; 
    scanf("%d", &number);

    for (int i = 1; i < number; ++i) {
        if (number % (i + 1) == 0) {
            divisor_count++;
        }
    }

    printf("%d\n", divisor_count);
    return 0;
    }
