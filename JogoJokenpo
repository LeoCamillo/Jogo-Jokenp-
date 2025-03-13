#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    
    int opcao, escolhaJogador, escolhaComputador; //Criação das variaveis

    srand(time(0)); //usa o tempo atual do sistema (em segundos) como semente para o gerador de números aleatórios.

    //Menu inicial do jogo!
    printf("### Jogo de Jokenpô ### \n");
    printf("### Escolha uma opção (1, 2 ou 3). ### \n");
    printf("1. Inciar o jogo \n");
    printf("2. Regras do jogo \n");
    printf("3. Sair do jogo \n");
    printf("Escolha: ");
    scanf("%d", &opcao);

    printf("#________________________________________________#\n");

    switch (opcao)
    {
    case 1: //Menu de escolha do jogo iniciado.
    printf("### JOKENPÔ ### \n");
    printf("### Escolha uma opção (1, 2 ou 3). ### \n");
    printf("1. Pedra \n");
    printf("2. Papel \n");
    printf("3. Tesoura \n");
    printf("Escolha: ");
    scanf("%d", &escolhaJogador);
    printf("#________________________________________________#\n");

    escolhaComputador = rand() % 3 + 1; //É feita essa conta para gera numeros até o 3, o +1 e para não pegar o 0

    switch (escolhaJogador) //Escolha do jogador
    {
    case 1:
    printf("Jogador: Pedra - ");
        break;

    case 2:
    printf("Jogador: Papel - ");
        break;

    case 3:
        printf("Jogador: Tesoura - ");
            break;
    
    default:
    printf("Opção Invalida.");
        break;
    }

    switch (escolhaComputador) //Escolha do Computador
    {
    case 1:
    printf("Computador: Pedra \n");
        break;

    case 2:
    printf("Computador: Papel \n");
        break;

    case 3:
        printf("Computador: Tesoura \n");
            break;
    }

    if (escolhaJogador == escolhaComputador) //Lógica do jogo sendo aplicada
    {
        printf("## O Jogo Empatou ##\n");
    }
    else if ((escolhaJogador == 1) && (escolhaComputador == 3) || (escolhaJogador == 2) && (escolhaComputador == 1) ||
     (escolhaJogador == 3) && (escolhaComputador == 2)) 
     {

        printf("## Parabéns, você Ganhou! ##\n");
     }
     else {
        printf("## Você Perdeu! ##\n");

     }

     printf("#________________________________________________#\n");

     break;

        case 2: //Regras do jogo
        printf("# Regras do jogo jokenpô #\n");
        printf("# Escolha uma opção entre 1. Pedra, 2. Papel ou 3. Tesoura.\n");
        printf("A Pedra ganha da tesoura e perde para o papel,\n");
        printf("O Papel perde para a tesoura e ganha da pedra e A Tesoura perde para a pedra e ganah do papel. #\n");
        printf("# O computador joga um numero aleatório de 1 a 3, e no final vemos quem ganhou, boa sorte! #\n");
        printf("#__________________________________________________________________________________________________#\n");

        break;
        case 3: //Para sair do jogo
        printf("# Saindo do jogo... #\n");
        break;

    default:
        break;
    }
    
    return 0;
}
