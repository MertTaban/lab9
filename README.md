# lab9
//C code to check whether a number is palindrome or not

#include <stdio.h>

int main()
{
    int num, temp, reversed = 0, rem;

    printf("Enter a number: ");
    scanf("%d", &num);

    temp = num;

    while (temp != 0)
    {
        rem = temp % 10;
        reversed = reversed * 10 + rem;
        temp = temp / 10;
    }

    if (num == reversed)
        printf("%d is a palindrome.\n", num);
    else
        printf("%d is not a palindrome.\n", num);

    return 0;
}


........................................................


// Faktöriyel hesaplama programý

#include <stdio.h>

main(){
	
	int i, sayi, faktoriyel;
	
	printf("Faktoriyeli Hesaplanacak Sayiyi Giriniz:");
	scanf("%d", &sayi);
	
		for(i=1; i<=sayi; i++)
			{
			faktoriyel *= i;
			}
	printf("Sonuc: %d", faktoriyel);
	
}

.....................................................



// Üç sayıdan en büyüğünü bulan program

#include <stdio.h>

main(){
	
	int a,b,c;
	
	printf("1. Sayiyi Giriniz:");
	scanf("%d", &a);
	printf("2. Sayiyi Giriniz:");
	scanf("%d", &b);
	printf("3. Sayiyi Giriniz:");
	scanf("%d", &c);
	
	if (a>b && a>c){
		printf("Birinci Sayi En Buyuk");
	}
	else if(b>a && b>c){
		printf("Ikinci Sayi En Buyuk");
	}	
	else{
		printf("Ucuncu Sayi En Buyuk");
	}

	
	
}


.........................................



