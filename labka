#include <stdio.h>

long double e_in_x( unsigned long long n) {
    long double x = 1.0;
    long double sum = 1.0;
    long double elem = x;
    for (unsigned long long i = 1; i < n; i++) {
        sum += elem;
        elem = elem * x / (i + 1);
    }
    return sum;

}

int main() {

    
    unsigned long long n = 6081081081;
    long double out_sum = 1.0;

    out_sum = e_in_x(n);
    printf("Tailor's summa of e^x: %Lf\n", out_sum);

    return 0;
}
