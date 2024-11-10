# PT1LE2
//Question 7
/*#include<iostream>
using namespace std;

int main()
{
		int p;
		char ans;
		
		cout<<"Enter your current lotalty points: ";
		cin>>p;

	do{
		
		if(p>=100)
		{
			if(p>=500)
			{
				if(p<1000)
				{
					cout<<"Discount: 10%"<<endl;
					p=p-500;
				}
				else
				{
					cout<<"Discount: 15%"<<endl;
					p=p-1000;
					
				}
			}
			else
			{
				cout<<"Discount: 5%"<<endl;
				p=p-100;
			}
		}
		else
		{
			cout<<"Insufficient points to redeem, You need at least 100 points. "<<endl;
			break;
		}
		
			
			cout<<"Remaining points: "<<p<<endl;
			if(p<100)
			{
				cout<<"Insufficient points to continue redeeming. "<<endl;
				break;
			} 
		
				cout<<"Do you want to redeem more points? (y/n): ";
				cin>>ans;
			
	}while(ans=='y');
	
	cout<<"Thank you for using the loyalty points redemption program! ";
	
	return 0;
}*/
