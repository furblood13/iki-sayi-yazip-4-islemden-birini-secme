# iki-sayi-yazip-4-islemden-birini-secme



#include <stdio.h>
#include<conio.h>
int main(){
	printf("MADE BY: FURBLOOD13 (github username)  \n\n");

	int a;
	int b;
	int secme;
	printf ("birinci sayiyi giriniz:");
	scanf("%d", &a);
	printf ("ikinci sayiyi giriniz:");
	scanf("%d" , &b);
	
	
	printf("asagidakilerden birini seciniz");
	printf("\n [1]-toplama islemi");
	printf("\n [2]-cikarma islemi");
	printf("\n [3]-carpma islemi");
	printf("\n [4]-bolme islemi");
	printf("\n LUTFEN BI SECIM YAPINIZ:");
	scanf("%d" , &secme);
	
	switch(secme){
		
	case 1:printf("toplam sonucu: %d" , a+b); break;
	case 2:printf("cikarma sonucu: %d" , a-b); break;
	case 3:printf("carpim sonucu: %d" , a*b); break;
	case 4:printf("bolum sonucu: %d" , a/b); break;
	
	 default: printf("aleti bozdun amk tekrar baslat");
		
		
		
		
		
	}
	
	getch();
	 
	
	 	
	 	return 0;
	 	
	 	
	 	
	 }
	
	
	
	
	
	
	
	
	
	

