# algoritmo-bm
Salario aumento //

#include<stdio.h>
int cargo;
float sal,aum,nsal;

int main(){
	printf("codigo do cargo:");
	scanf("%d",&cod);
	printf("\nqual o seu salrio:");
	scanf("%f",&sal);
if(cod==1 || cod==2 || cod==3){
  if(cod==1){
	aum=sal*0.40;
	nsal=sal+aum;
	printf("\nescrituario-aumento %.2f - novo sal R$%.2f",aum,nsal);
 }
 else if(cod==2){
	aum=sal*0.20;
	nsal=sal+aum;
	printf("\nSecretario-aumento %.2f - novo sal R$%.2f",aum,nsal);
 }
 else{
    aum=sal*0.10;
	nsal=sal+aum;
	printf("\ngerente-aumento %.2f - novo sal R$%.2f",aum,nsal);
 }
else{
 printf("\n******codigo invalido*******");
 }
}

return 0;
}

