 #include <iostream>
 using namespace std;
 
  int main()
{
	string snacks[3] [4] = {
	    { "Galaxy Silk","Mars Bar", "Snickers", "Bounty"},//first row
	    {"Falourved Youghurt","Oman Chips", "Oreo","Lays"},//second row
	    { "Apple","Banana","Orange", "Drangon Fruit"}// third row
	        
	    };
	    for (int i = 0; i < 3; i++)
	    {
	        for (int j = 0; j < 2; j++){
	            cout<<snacks[i] [j]<< " " ;
	        }
	    cout<<endl;
	}
}
