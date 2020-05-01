    #include <stdio.h>
    #include <stdlib.h>

    int main() {
    
    int sicaklik;
    float ikincisicaklik;

    printf("Sicakligi giriniz (oC): ");
    scanf("%d", &sicaklik);

    printf("-----------------------------\n");

    ikincisicaklik= ((sicaklik/100)*180)+32;

    printf("Girilen %d oC, %f Fahrenhayt", sicaklik, ikincisicaklik);

    return 0; }
