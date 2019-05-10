#include <iostream>
#include <string>
#include <ctime>

using std::cout;

void same(std::string a)
{

	std::string hold, temp;
	for (int i = 0; i < a.size(); i++) //could optimize it with  a.size() / 2, only if input string has letters and numbers.
	{
		if (isalnum((a[i])))
		{
			temp += tolower(a[i]);
		}	
		if (isalnum(a[a.size() - (i + 1)]))
		{
			hold += tolower(a[a.size() - (i + 1)]);
		}
	}
	(hold.compare(temp)) ? cout << "False" : cout << "True";
}

int main()
{
	std::string a = "Don't nod";
	same(a);
}
