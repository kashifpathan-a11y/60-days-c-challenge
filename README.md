# 60-days-c-challenge
#include <stdio.h>

int main()

{

float basic_salary, hra_percent, da_percent, tax_percent;

float hra, da, tax, gross_salary;

printf("Basic salary: \n");

 scanf("%f",&basic_salary);

printf("Hra percent : \n");

scanf("%f",&hra_percent);

printf("Da percent : \n");

scanf("%f", da_percent);

printf("Tax percent :\n");

 scanf("%f",&tax_percent);


hra = basic_salary*(hra_percent/100);

printf("hra = %f\n", hra);

da = basic_salary*(da_percent/100);

print("da = %f\n",da);

tax = basic_salary*(tax_percent/100);

printf("tax = %f\n", tax);

gross_salary = basic_salary+hra+da-tax;

printf("gross salary = %f\n", gross_salary);

Printf("Is gross salary  > 50000?%d\n" ,gross_salary  > 50000);
return 0;
}
