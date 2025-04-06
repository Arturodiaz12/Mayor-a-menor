
#include <stdio.h>

int main() {
    int num1, num2, num3, num4, num5, aux;

    printf("Ingrese el primer número: ");
    scanf("%d", &num1);

    printf("Ingrese el segundo número: ");
    scanf("%d", &num2);

    printf("Ingrese el tercer número: ");
    scanf("%d", &num3);

    printf("Ingrese el cuarto número: ");
    scanf("%d", &num4);

    printf("Ingrese el quinto número: ");
    scanf("%d", &num5);

    // Ordenar de mayor a menor usando intercambio
    if (num1 < num2) { aux = num1; num1 = num2; num2 = aux; }
    if (num1 < num3) { aux = num1; num1 = num3; num3 = aux; }
    if (num1 < num4) { aux = num1; num1 = num4; num4 = aux; }
    if (num1 < num5) { aux = num1; num1 = num5; num5 = aux; }

    if (num2 < num3) { aux = num2; num2 = num3; num3 = aux; }
    if (num2 < num4) { aux = num2; num2 = num4; num4 = aux; }
    if (num2 < num5) { aux = num2; num2 = num5; num5 = aux; }

    if (num3 < num4) { aux = num3; num3 = num4; num4 = aux; }
    if (num3 < num5) { aux = num3; num3 = num5; num5 = aux; }

    if (num4 < num5) { aux = num4; num4 = num5; num5 = aux; }

    // Mostrar resultado
    printf("Los números ordenados de mayor a menor son:\n");
    printf("%d\n", num1);
    printf("%d\n", num2);
    printf("%d\n", num3);
    printf("%d\n", num4);
    printf("%d\n", num5);

    return 0;
}
