#include <stdio.h>

int main(){
    char nome_pais [30];
    char codigo_carta [15];
    int populacao;
    float area_km2;
    float PIB;
    int num_cartas;

    printf("Digite o nome do país: ");
    scanf("%s", nome_pais);
    printf("O pais é: %s\n", nome_pais);

    printf("Digite o código da carta: ");
    scanf("%s", codigo_carta);
    printf("O código da carta é: %s\n", codigo_carta);

    printf("Digite a população: ");
    scanf("%d", &populacao);
    printf("A população é: %d\n", populacao);

    printf("Digite a área em km2: ");
    scanf("%f", &area_km2);
    printf("A área em km2 é: %f\n", area_km2);

    printf("Digite o PIB: ");
    scanf("%f", &PIB);
    printf("O PIB é: %f\n", PIB);

    printf("Digite o número de cartas: ");
    scanf("%d", &num_cartas);
    printf("O número de cartas é: %d\n", num_cartas);

    return 0;
}
