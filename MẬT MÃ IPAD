#include <bits/stdc++.h>
using namespace std;
int main()
{
	int t;
	cin >> t;
	while (t--)
	{
		string s1, s2;
		cin >> s1 >> s2;
		string check = "";
		for (int j = 0; j < s2.size(); j++)
		{
			if (s2[j] >= 'A' && s2[j] <= 'J')
				check.push_back(s2[j] - 17);
			else if (s2[j] >= 'K' && s2[j] <= 'T')
				check.push_back(s2[j] - 27);
		}
		if (check == s1)
			cout << "YES\n";
		else
			cout << "NO\n";
	}
}
