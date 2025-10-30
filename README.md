#include <stdio.h>

/*
  Programa: Simulação de movimentos de peças de xadrez
  Peças: Torre, Bispo e Rainha
  Estruturas de repetição utilizadas:
    - Torre: for
    - Bispo: while
    - Rainha: do-while
  Autor: Fabiane Freitas
  Objetivo: Demonstrar o uso de estruturas de repetição em C simulando movimentos no tabuleiro
*/

int main() {
    // ======================
    // Movimento da TORRE
    // ======================
    int casasTorre = 5;
    printf("Movimento da Torre (5 casas para a direita):\n");

    for (int i = 1; i <= casasTorre; i++) {
        printf("Direita (%d casa)\n", i);
    }

    printf("\n");

    // ======================
    // Movimento do BISPO
    // ======================
    int casasBispo = 5;
    int contador = 1;
    printf("Movimento do Bispo (5 casas na diagonal para cima e à direita):\n");

    while (contador <= casasBispo) {
        printf("Cima, Direita (%d casa)\n", contador);
        contador++;
    }

    printf("\n");

    // ======================
    // Movimento da RAINHA
    // ======================
    int casasRainha = 8;
    int j = 1;
    printf("Movimento da Rainha (8 casas para a esquerda):\n");

    do {
        printf("Esquerda (%d casa)\n", j);
        j++;
    } while (j <= casasRainha);

    printf("\nSimulação concluída!\n");

    return 0;
}
