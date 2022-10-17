# c-plus-plus-
#include<iostream>
#include<conio.h>
using namespace std;
class add
{
   float c;
public:

   add() 
   {
       cout << "sum is:";
   }

   add(float x, float y) 
   {
       c = x + y;
   }

   void display() 
   {
       cout << c;
   }
};

float main()
 {

   float x, y;

   cout << "Enter two numbers:";
   cin >> x>>y;

   add t;
   add tt(x, y);
   tt.display();
   getch();
   return 0;
}
