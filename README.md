# c-plus-plus-
#include<iostream>
#include<conio.h>
using namespace std;
class add 
{
   int c;
public:

   add() 
   {
       cout << "Sum is:";
   }

   add(int a, int b) 
   {
       c = a + b;
   }

   void display() 
   {
       cout << c;
   }
};

int main()
 {

   int a, b;

   cout << "Enter two numbers:";
   cin >> a>>b;

   add t;
   add tt(a, b);
   tt.display();
   getch();
   return 0;
}
