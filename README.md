# PROGRAMMING-FUNDERMENTALS
AN ASSIGNMENT
 #include <iostream>

// 10962171 PRINCESS LILY EYRAM APREKU; 
using namespace std;


int main()
{
    int i = 1, average = 0, sum = 0;
  while( i++ <= 10000 ) {
    if( i%2 == 0 ) {
      sum += i;
      average ++;
    }
  }

  cout << " Sum of all even numbers is "<< sum << endl;

  cout << " Average is "<< (sum / average ) << endl;

  return 0;
}
