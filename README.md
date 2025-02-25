//lanchonete Ratos Fritos
//programa para calculor as vendas de uma lanchonete 

#include <stdio.h>
#include <conio.h>
#include <stdlib.h>
#include <string.h>

int main() {

    int iMenuPrincipal, iMenuLanches, iMenuBebidas, iMenuSobremesas; //variáveis de menu
    float valorLanches = 0, valorBebidas = 0, valorSobremesas = 0, valorTotal; //variáveis do cliente
    int promocao; //quantidades de pés de moleque
    
    // Variáveis de relatório
    // QUANTIDADES
    int qMisto = 0, qOvo = 0, qHotDog = 0, qXSal = 0, qXBac = 0, qTudo = 0;
    int qPing = 0, qTub = 0, qSoda = 0, qSuco = 0, q51 = 0;
    int qArroz = 0, qAcai = 0, qGel = 0, qPe = 0, qPud = 0;
    int qLanches = 0, qBebidas = 0, qSobrem = 0;

    // Percentuais de produtos vendidos
    float totalMisto, totalOvo, totalHotDog, totalXSal, totalXBac, totalTudo;
    float totalPing, totalTub, totalSoda, totalSuco, total51;
    float totalArroz, totalAcai, totalGel, totalPe, totalPud;
    float totalLanches, totalBebidas, totalSobrem;

    /* (do) é o laço de repetição que o bloco de comandos será
       executado enquanto o usuário não escolher a opção SAIR (5)*/
    do {
    	   
		} while(iMenuPrincipal != 6); // Termina o loop quando a opção 6 for escolhida

    return 0;
}
