#include<stdio.h>
#include<conio.h>
#include<iostream>

/*int main(){
	int satir = 0;
	int bosluk = 0;
	for(int satir=5; satir>0; satir--){
		for(int yildiz=satir; yildiz>0; yildiz--){
		
		printf("*");
	}
	printf("\n");
	} 
	return 0;
}
*/
/*int main(){
      
    int a=1;
    int c=5;
	for(int i=11; i>0; i-=2){
		for(int j=i;j>0;j--){
			printf("*");
	
		}
		printf("\n");
		
	
		for(int b=0; b<a;b++){
			printf(" ");
			
		}
	
	a++;
    }
printf("\n");
   for(int i=1;i<=11;i+=2){
   			 for(int b=0; b<c;b++){
			printf(" ");
		
		}
       
   	   for(int j=1;j<=i;j++)
   	   {
   		printf("*");
   		
	   }
	   
	   
	   printf("\n");
	
	 c--;	

   }
   
}*/


/*int main(){
	int i,j,say;
	printf("Bir sayi giriniz:");
	scanf("%d",&say);
	for(i=0;i<say;i++){
		for(j=0;j<i;j++){
			printf(" ");
		}
		for(j=0;j<2*(say-i)-1;j++){
			printf("*");
		}
		printf("\n");
		
	}
	for(i=say-2;i>=0;i--)
{
	for(j=0;j<i;j++){
		printf(" ");
		
	}
	for(j=0;j<2*(say-i)-1;j++)
{
	printf("*");
	
	}
	printf("\n");
		}	
		return 0;
}*/


/*int main(){
	int satir, x;
	scanf("%d", &satir);
	x = satir;
	for(int i = 1; i < satir + 1; i++){
		for(int j = 0; j < i; j++){
			printf("*");
		}
	    for(int j = 0; j < x * 2 - 3; j++){
	    	printf(" ");
		}
		for(int j = 0; j < i; j++){
			if(j == satir - 1){
				break;
			}
			printf("*");
		}
		printf("\n");
		x += -1;
	}
	x += 2;
	for(int i=1; i<satir; i++)
	{
		for(int j = 0; j < satir - i; j++){
			printf("*");
		}
		for(int j = 0; j < x * 2 - 3; j++){
			printf(" ");
		}
		for(int j = 0; j < satir - i; j++){
			if(j == satir - 1){
				break;
			}
			printf("*");
		}
		printf("\n");
		x += 1;
	}

	return 0;
}*/











