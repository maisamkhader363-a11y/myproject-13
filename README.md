#include<iostream>
using namespace std;
int main()
{
	int speed=0;
	char  inSchoolZone=' ';
	

	int fine = 0;

	cout << "Enter the speed of the vehicle (in km/h): ";
	cin >> speed;
	if (speed < 0 || speed>200)
	{
		cout << "Invalid speed.";
	}
	else if (speed <= 60)
	{
		cout << "No fine.Drive safely!";

	}
	 else if (speed > 60)
	 {
		 cout << "Is the vehicle in a school zone? (y/n): ";
		 cin >> inSchoolZone;
	 if (inSchoolZone == 'y')
		 
		
	 	if (speed <= 80)
			
				cout << "Fine: $100)";
			
			else// speed >80 
			
				cout << "Fine: $200";
			}
		if (inSchoolZone == 'n')
			
	  if (speed <= 100)
	 {
		 cout << "Fine:$50";
	 }
	 else
	 {
		 cout << "Fine:$150";
   }
     	 return 0;
	 }
	 return 0;
