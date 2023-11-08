# variables-in-progarming
Home Work 


#include<iostream>
using namespace std;

int main()
{
    
     int num1 = 20 ;
     int num2 = 60 ;
     int num3 = 100 ;
     int num4 = 140 ;
     
     int result ;
     
     result = num1 + num2 + num3 ;
     
     num1 = num3 ;
     num3 = num2 + num1 + result ;
     num2 = num3 - num2 - result ;
     
     num3 = num2 + num4;
     num1 = num2 ;
     num3 = num1 + result ;
     num1++;
     num1++;
     
     cout << " sum of " << num1 << "," << num2 << "," << num3 << " and " << num4 << " is " << result ;
     cout << " \n \n \t " ;
          cout << "  'CS 23\\303'";
          cout << " \n \t Date 7 Nov 2023 " ;
    return 0;
}
