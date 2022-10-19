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

   add(float x,float y, float z) 
   {
       c = x + y + z;
   }

   void display() 
   {
       cout << c;
   }
};

float main()
 {

   float x, y, z;

   cout << "Enter three numbers:";
   cin >> x>>y>>z;

   add t;
   add tt(x, y,z);
   tt.display();
   getch();
   return 0;
}
