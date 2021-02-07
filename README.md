 # include <iostream>
using namespace std;

int main()
{
	// Declare all the variables for the program. In future, months could be an object
	// Months could be counted using a loop to remove the hard coding that is going on right now
	// Proceeding as requested though based on the initial problem requirements
	char month1[20], month2[20], month3[20];
	// Remember that a string in C++ is actually a one dimensional array of characters which is terminated by  a null character \0
	double rainfall1, rainfall2, rainfall3, average;
	
	cout << "Welcome to the average rainfall calculator! \n";
	cout << "This program will ask you to enter 3 (hard coded) months of data 	as well as the corresponding monthly rain fall. \n";
	cout << "The monthly average will then be calculated for each of the months!\n\n";
	
	cout << "What is the name of the first month you would like to enter? \n";
	cin >> month1;
	cout << "How much rainfall did you have in mm for " << month1 << "?\n";
	cin >> rainfall1;

	cout << "What is the name of the second month you would like to enter? \n";
	cin >> month2;
	cout << "How much rainfall did you have in mm for " << month2 << "?\n";
	cin >> rainfall2;
	
	cout << "What is the name of the third month you would like to enter? \n";
	cin >> month3;
	cout << "How much rainfall did you have in mm for " << month3 << "?\n";
	cin >> rainfall3;
	
	// Calculate the output and return the values to the user
	average = (rainfall1 + rainfall2 + rainfall3) / 3;
	cout << "Thank you for using the monthly rainfall calculator program! \n";
	cout << "For the months of " << month1 << " " << "and" << month2 << " " << "and" << month3 << " " << "\n the average monthly rainfall is " << average << "." ;
}
