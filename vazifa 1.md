#include <iostream>

using namespace std;
int main() {
	float x, y;
	cout << "(y-2)/x +(y-1)/(x-1)+y/(x-2)-x*(x-1)*(y-2) ni hisoblang" << endl;
	cout << "x=";
	cin >> x;
	cout << "y=";
	cin >> y;
	cout << "(y-2)/x +(y-1)/(x-1)+y/(x-2)-x*(x-1)*(y-2)" << endl;

	cout << "("<<y<<" - 2)/("<<x<<")+("<<y<<"-1)/("<<x<<"-1)+("<<y<<")/("<<x<<"-2)-("<<x<<")*("<<x<<"-1)*("<<y<<"-2) = " << (y - 2) / x + (y - 1) / (x - 1) + y / (x - 2) - x * (x - 1) * (y - 2) << endl;
	return 0;
}
