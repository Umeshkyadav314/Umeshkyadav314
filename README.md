
Ramesh's basic salary is input through the keyboard. His dearness allowance is 40% of basic salary, and house rent allowance is 20% of basic salary. Write a program to calculate his gross salary.

#include <stdio.h>

int main()
{
    float basic_salary,dearness_allowance,house_rent_allowance,gross_salary;
    printf("enter basic_salary:\n");
    scanf("%f",&basic_salary);
    dearness_allowance=.40*basic_salary;
    house_rent_allowance=.20*basic_salary;
    
    gross_salary=basic_salary+dearness_allowance+house_rent_allowance;
    
   printf("\n basic_salary:%.2f",gross_salary);
   printf("\n dearness_allowance:%.2f",gross_salary);
   printf("\n house_rent_allowance:%.2f",gross_salary);
   
   printf("\n\n gross_salary:%.2f",gross_salary);
   
    return 0;
}
