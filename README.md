# lecture-10

decending stars 7 exercise

#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)
	{ //execute the outer loop 5 times 
		for (int j = 1; j <=i; j++)
		{//execute the inner loop 5 x 5 times
			cout << "*"; //print 5 stars
		}
		cout << endl; //print to a new console line 
	}


}
  
  
  cube exercise
  
  
  #include <iostream>
#include <string>
using namespace std;
int main()
{
	int r;
	cout << "Enter a number to find the cube" << endl;
	cin >> r;
	for (int x = 1; x <= r; x++)
	{
		cout << "\nNumber is " << x << " the cube is ";
		int y = x;
		y=y* y* y;
		cout << y;
	}

}
             

9s exercise
             
             
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int sum = 0;
	
	for (int x = 100; x <= 200; x++)
	{
		if (x % 9 == 0)
		{
			cout << "\nNumber is " << x << endl;
					
			sum = sum + x;
		
					}
		
		
	}
	cout << "The sum is " << sum << endl;
}
             
             
rising star 5 exercise
             
            
             
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)
	{ //execute the outer loop 5 times 
		for (int j = 1; j <=i; j++)
		{//execute the inner loop 5 x 5 times
			cout << "*"; //print 5 stars
		}
		cout << endl; //print to a new console line 
	}


}
  
  
  
rise and fall exercise
  
  
  
  #include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)
	{ //execute the outer loop 5 times 
		for (int j = 1; j <= i; j++)
		{//execute the inner loop 5 x 5 times
			cout << "*"; //print 5 stars
		}
		cout << endl; //print to a new console line 
	}


	for (int i = 1; i <= 5; i++) {
		for (int j = i; j <= 5; j++) { //execute the inner loop 5 times
			cout << "*"; //print reducing lines of stars
		}
		cout << endl; //print to a new console line 
	}


}

             
             
