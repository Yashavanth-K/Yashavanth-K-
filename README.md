# Yashavanth-K-
Full stack of developer 

\\ Simple Calculator 

#include <stdio.h>
#include <conio.h>
int main() 
{
char op;
double num1, num2;
printf("Enter an operator (+, -, *, /): ");    
scanf("%c", &op);
printf("Enter two operands: ");
scanf("%lf %lf", &num1, &num2);
switch (op) {
case '+':
printf("%lf + %lf = %f\n", num1, num2, num1 + num2); 
break;
case '-':
printf("%lf - %lf = %lf\n", num1, num2, num1 - num2);
break;
case '*':
printf("%lf * %lf = %lf\n", num1, num2, num1 * num2);
break;
case'/';
 if(num2!=0)                                             
printf("%lf / %lf = %lf\n", num1, num2, num1 / num2);
else  
printf("Error! Division by zero.\n");
break;                                                                                                                                                    
default:
printf("Error! Operator is not correct\n");
}
return 0;
}
