// S2_JoshuaMacaballug.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
#include <math.h>
#include <string>
using namespace std;
int main()
{
	cout << "Welcome, please enter your full name:\n";
	{
		{
			string userName;
			getline(cin, userName);
			cout << "Hello "<<userName<<", Please enter a valid number: \n";
		}
		int x, fact = 1;
		cin >> x;
		for (int y = x; y > 0; y--)
		{
			fact = y * fact;
		}
		cout << "The factorial of "<<x<<" is:" << fact;
	}
	{
		cout << "\n\nThis code will count from 0 to 10:\n";
		for (int x = 0; x < 11; x++) {
			cout << "y x " << x << "\n";
		}
	}
	cout << "\nPlease enter a valid number again:";
	int f;
	cin >> f;
	cout << "\nPower from 1-10 for " << f << " is: \n" << endl;
	int p = 1;
	do {
		cout << f << " powered to " << p << " = " << pow(f, p) << endl;
		p++;
	} while (p <= 10);
}


