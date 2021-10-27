# c-plus-plus-
#include<iostream>
#include<conio.h>
using namespace std;
class sub 
{
   float c;
public:

   add() 
   {
       cout << "Diff is:";
   }

   sub(float x, float y) 
   {
       c = x - y;
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

   sub t;
   sub tt(x, y);
   tt.display();
   getch();
   return 0;
}
