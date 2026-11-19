'''c
include <stdio.h>

int main() {
  double x = 0.5;
  double pi = 3.14159265358979323846;

  int n;
  printf("Введіть значення n: ");
  scanf("%d", &n);

  int op_c = 0;

  double res = pi / 2.0;
  op_c += 2; // = та /

  op_c += 1; // i = 0
  for (int i = 0; i <= n; i++) {
    op_c += 1; // i <= n

    double res_sign = 1;
    op_c += 1; // res_sign = 1

    op_c += 1; // j = 1
    for (int j = 1; j <= i; j++) {
      op_c += 1; // j <= i
      res_sign *= -1;
      op_c += 3; // *= (* та =) і унарний мінус (-1)
      op_c += 1; // j++
    }
    op_c += 1; // j <= i 
    double res_x_power = 1;
    op_c += 1; // res_x_power = 1

    op_c += 1; // j = 1
    for (int j = 1; j <= 2 * i + 1; j++) {
      op_c += 3; // 2 * i, + 1, j <=
      res_x_power *= x;
      op_c += 2; // *= (* та =)
      op_c += 1; // j++
    }
    op_c += 3; // 2 * i, + 1, j <= 

    res -= res_sign / ((2 * i + 1) * res_x_power);
    op_c += 6; // 2 * i, + 1, * res_x_power, /, -= (- та =)

    op_c += 1; // i++
  }
  op_c += 1; // i <= n 

  printf("Результат обчислень: %.7lf\n", res);
  printf("Кількість операцій: %d\n", op_c);

  return 0;
}
'''
