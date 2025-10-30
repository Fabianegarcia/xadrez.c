#include <stdio.h>

int main() {
    // ------------------------------
    // Simulação do movimento das peças de xadrez
    // ------------------------------

    // 1️⃣ Torre – usa estrutura FOR
    // Move-se 5 casas para a direita
    int casasTorre = 5;
    printf("Movimento da TORRE:\n");
    for (int i = 1; i <= casasTorre; i++) {
        printf("Direita\n");
    }

    // ------------------------------

    // 2️⃣ Bispo – usa estrutura WHILE
    // Move-se 5 casas na diagonal: Cima e Direita
    int casasBispo = 5;
    int contadorBispo = 1;

    printf("\nMovimento do BISPO:\n");
    while (contadorBispo <= casasBispo) {
        printf("Cima, Direita\n");
        contadorBispo++;
    }

    // ------------------------------

    // 3️⃣ Rainha – usa estrutura DO-WHILE
    // Move-se 8 casas para a esquerda
    int casasRainha = 8;
    int contadorRainha = 1;

    printf("\nMovimento da RAINHA:\n");
    do {
        printf("Esquerda\n");
        contadorRainha++;
    } while (contadorRainha <= casasRainha);

    // ------------------------------

    return 0;
}
