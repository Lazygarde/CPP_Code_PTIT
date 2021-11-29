#include <bits/stdc++.h>
using namespace std;

int checkngay(string s)
{
	for (int i = 0; i < s.size(); i++)
	{
		if (s[i] == '/')
			return 1;
	}
	return 0;
}

struct data
{
	string ngay, ten, so;
	void setngay(string x)
	{
		string s;
		for (int i = 0; i < x.size(); i++)
		{
			if ((x[i] >= '0' && x[i] <= '9') || x[i] == '/')
			{
				s.push_back(x[i]);
			}
		}
		ngay = s;
	}
	void setten(string x)
	{
		ten = x;
	}
	void setso(string x)
	{
		so = x;
	}
	void Output()
	{
		cout << ten << ": " << so << " " << ngay << "\n";
	}
	string getten()
	{
		return ten;
	}
};

bool cmp(data a, data b)
{
	string x = a.getten(), y = b.getten();
	vector<string> xx, yy;
	string u;
	for (int i = 0; i < x.size(); i++)
	{
		if (x[i] != ' ')
			u.push_back(x[i]);
		else
		{
			xx.push_back(u);
			u.clear();
		}
	}
	xx.push_back(u);
	u.clear();
	for (int i = 0; i < y.size(); i++)
	{
		if (y[i] != ' ')
			u.push_back(y[i]);
		else
		{
			yy.push_back(u);
			u.clear();
		}
	}
	yy.push_back(u);
	u.clear();
	if (xx[xx.size() - 1] == yy[yy.size() - 1])
	{
		return xx < yy;
	}
	return xx[xx.size() - 1] < yy[yy.size() - 1];
}
int main()
{
	freopen("SOTAY.txt", "r", stdin);
	freopen("DIENTHOAI.txt", "w", stdout);
	int dem = 1;
	string s, ngay;
	data a;
	vector<data> l;
	while (getline(cin, s))
	{
		if (checkngay(s) == 1)
		{
			ngay = s;
		}
		else
		{
			if (dem == 1)
			{
				a.setten(s);
				a.setngay(ngay);
			}
			else
			{
				a.setso(s);
				a.setngay(ngay);
			}
			dem++;
		}
		if (dem > 2)
		{
			l.push_back(a);
			dem = 1;
		}
	}
	sort(l.begin(), l.end(), cmp);
	for (int i = 0; i < l.size(); i++)
		l[i].Output();
	return 0;
}
