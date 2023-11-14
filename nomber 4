#include <iostream>

using namespace std;

int main()
{
	setlocale(0, "");

	long long n = 1;

	for (int i = 1; i <= 10; i++)
	{
		long long subSum = 0;

		for (int j = 1; j <= i; j++)
		{
			subSum += j;
		}
		n *= subSum;
	}

	cout << n << endl;


	return 0;
}
