#include <iostream>

int determinant(int a1, int a2, int a3, int b1, int b2, int b3, int c1, int c2, int c3) {
    return a1 * (b2 * c3 - b3 * c2) -
           a2 * (b1 * c3 - b3 * c1) +
           a3 * (b1 * c2 - b2 * c1);
}

int main() {
    int a1 = 1, a2 = 0, a3 = -2;
    int b1 = -2, b2 = 4, b3 = 5;
    int c1 = 0, c2 = -3, c3 = 1;

    int det = determinant(a1, a2, a3, b1, b2, b3, c1, c2, c3);

    std::cout << "Определитель матрицы: " << det << std::endl;

    return 0;
}
