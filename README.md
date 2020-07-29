#include <iostream>
using namespace std;;
int main()
{
	int A,B;
	cout << "Enter A number : ";
	cin >> A;
	cout << "Enter B number : ";
	cin >> B;
	cout << "Largest : " << ((A >B) ? A : B) << endl;
	cout << "Smallest : " << ((A <B) ? A : B) << endl;
	getchar();
	getchar();
}
