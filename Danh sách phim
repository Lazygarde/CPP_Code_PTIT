#include <bits/stdc++.h>
using namespace std;

string chuanHoa(int a)
{
	string End = "";
	while (a)
	{
		End = (char)(a % 10 + '0');
		a /= 10;
	}
	while (End.size() < 3)
		End = '0' + End;
	return End;
}

class TheLoai
{
public:
	string ma, name;
	static int ID;
	friend istream &operator>>(istream &input, TheLoai &obj)
	{
		TheLoai::ID++;
		obj.ma = "TL" + chuanHoa((TheLoai::ID));
		getline(input, obj.name);
		return input;
	}
};

class Phim
{
public:
	int eps;
	string ma, name, date, kind, xo;
	static int ID;
	friend istream &operator>>(istream &input, Phim &obj)
	{
		Phim::ID++;
		obj.ma = "P" + chuanHoa((Phim::ID));
		input >> obj.kind;
		input >> obj.date;
		cin.ignore();
		getline(input, obj.name);
		input >> obj.eps;
		return input;
	}
	friend ostream &operator<<(ostream &output, Phim &obj)
	{
		cout << obj.ma << " " << obj.kind << " " << obj.date << " " << obj.name << " " << obj.eps << endl;
		return output;
	}
};

int TheLoai::ID = 0;
int Phim::ID = 0;

bool cmp(Phim a, Phim b)
{
	int check[10] = {6, 7, 8, 9, 3, 4, 1, 2};
	for (int i = 0; i < 8; i++)
	{
		if (a.date[check[i]] < b.date[check[i]])
			return 1;
		if (a.date[check[i]] > b.date[check[i]])
			return 0;
	}
	if (a.name < b.name)
		return 1;
	if (a.name > b.name)
		return 0;
	if (a.eps > b.eps)
		return 1;
	return 0;
}

void process(TheLoai tl[], int n, Phim p[], int m)
{
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			if ((tl + j)->ma == (p + i)->kind)
			{
				(p + i)->kind = (tl + j)->name;
			}
		}
	}
	sort(p, p + m, cmp);
}

int main()
{
	int n, m;
	cin >> n >> m;
	cin.ignore();
	TheLoai tl[100];
	Phim p[1000];
	for (int i = 0; i < n; i++)
	{
		cin >> tl[i];
	}
	for (int i = 0; i < m; i++)
	{
		cin >> p[i];
	}
	process(tl, n, p, m);
	for (int i = 0; i < m; i++)
	{
		cout << p[i];
	}
}
