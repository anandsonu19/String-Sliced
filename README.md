# String-Sliced
#include <iostream>
#include<string>
using namespace std;
int main()
{
	string s;
	getline(cin, s);
	int j;
	cin>>j;
	int k;
	cin>>k;
		string r = s.substr(j, k);
		cout<<r<<"";
	//Write code here
}
