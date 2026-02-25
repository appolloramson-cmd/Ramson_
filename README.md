//calculator
#include <iostream>
using namespace std;

int main () {
     double num1 , num2;
     char op;
     
     cout << "Enter first number : ";
     cin >> num1;
     
     cout << " Enter operator (+,*,%,-,/): ";
     cin >> op;
     
     cout << " Enter second number: ";
     cin >> num2;
     
     double results;
     switch (op) {
       
       case '+' :
       results = num1 + num2;
       cout << "results = " << results;
       break;
       
       case '*' :
       results = num1 * num2;
       cout << " results = " << results;
       break;
       
       case '/' :
       results = num1 / num2;
       cout << " results = " << results;
       break;
       
       case '%' :
       results = num1 / num2;
       cout << " results = " << results;
       break;
       
     }
 return 0;
                   }      
     
