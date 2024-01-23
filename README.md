#include <iostream>

float suma(float valor1, float valor2);
float resta(float valor1, float valor2);
float multiplicacion(float valor1, float valor2);
float division(float valor1, float valor2);

int main() {
    float valor1, valor2, resultado;

    std::cout << "Ingrese el primer valor: ";
    std::cin >> valor1;

    std::cout << "Ingrese el segundo valor: ";
    std::cin >> valor2;

    resultado = suma(valor1, valor2);
    std::cout << "La suma es: " << resultado << std::endl;

    resultado = resta(valor1, valor2);
    std::cout << "La resta es: " << resultado << std::endl;

    resultado = multiplicacion(valor1, valor2);
    std::cout << "La multiplicacion es: " << resultado << std::endl;

    resultado = division(valor1, valor2);
        std::cout << "La division es: " << resultado << std::endl;
   
    return 0;
}

float suma(float valor1, float valor2) {
    return valor1 + valor2;
}

float resta(float valor1, float valor2) {
    return valor1 - valor2;
}

float multiplicacion(float valor1, float valor2) {
    return valor1 * valor2;
}

float division(float valor1, float valor2) {
    return valor1 / valor2;
}
