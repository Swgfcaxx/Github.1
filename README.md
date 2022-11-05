# Github.1
刚用Github的小白（在校大学生）
#include<iostream>
using namespace std;
int main()
{
float a, b, c;
	cout << "input a,b,c:";
	cin >> a >> b >> c;
	if (a + b > c && a + c > b && b + c > a)
		cout << "area=" << AREA(a, b, c) << endl;
	else
		cout << "It is not a triangle!" << endl;
system("pause");
return 0;
}
