
Ramesh's basic salary is input through the keyboard. His dearness allowance is 40% of basic salary, and house rent allowance is 20% of basic salary. Write a program to calculate his gross salary.





<!---
Umeshkyadav314/Umeshkyadav314 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>
int main()
{
    float basic_salary, dallowance, house_rent, gross_salary;
    printf("Enter Basic Salary:");
    scanf("%f",&basic_salary);

    dallowance = 0.4 * basic_salary;
    house_rent = 0.2 * basic_salary;

    gross_salary = basic_salary + dallowance + house_rent;
    printf("\n Basic Salary: %.2f",  basic_salary);
    printf("\n Dearness Allowance: %.2f", dallowance);
    printf("\n House Rent: %.2f", house_rent);
    printf("\n\nGross Salary: %.2f", gross_salary);

    return 0;
}
