# Rising-and-falling-stars
#for loop
#include<iostream>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)  //using nested for loop to print the pattern in ascending order
{
	for (int j = 1; j <= i; j++)
	{
		cout << "*";
	}
	cout << endl;
}
	for (int i = 1; i <= 4; i++) //using nested loop to print the pattern in descending order
	{
		for (int j = i; j <= 4; j++)
		{
			cout << "*";
		}
		cout << endl;
	}
	return 0;
}
