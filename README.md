# include <stdio.h>

int main() {
    int n, i, sayi, toplam = 0;

    printf("Kaç adet sayı gireceksiniz: ");
    scanf("%d", &n);

    // n adet sayı alınıyor ve toplanıyor
    for (i = 0; i < n; i++) {
        printf("Sayı %d: ", i+1);
        scanf("%d", &sayi);
        toplam += sayi;
    }

    // Toplam ekrana yazdırılıyor
    printf
