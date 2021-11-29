#include <bits/stdc++.h>
using namespace std;

string chuanHoa(int a)
{
	string End = "T";
	if (a >= 100)
		;
	else if (a >= 10)
		End += "0";
	else
		End += "00";
	End += to_string(a);
	return End;
}

class MonHoc
{
public:
	string ma, name;
	friend istream &operator>>(istream &input, MonHoc &obj)
	{
		input >> obj.ma;
		cin.ignore();
		getline(input, obj.name);
		return input;
	}
};

class LichThi
{
public:
	int eps;
	string macathi, mamonhoc, ngaythi, giothi, nhomthi, tenmonhoc;
	static int ID;
	friend istream &operator>>(istream &input, LichThi &obj)
	{
		LichThi::ID++;
		obj.macathi = chuanHoa((LichThi::ID));
		input >> obj.mamonhoc;
		input >> obj.ngaythi;
		input >> obj.giothi;
		input >> obj.nhomthi;
		return input;
	}
	friend ostream &operator<<(ostream &output, LichThi &obj)
	{
		cout << obj.macathi << " " << obj.mamonhoc << " " << obj.tenmonhoc << " " << obj.ngaythi << " " << obj.giothi << " " << obj.nhomthi << endl;
		return output;
	}
};

int LichThi::ID = 0;

string getphut(string x)
{
	string s = "";
	s += x[3];
	s += x[4];
	return s;
}

string getgio(string x)
{
	string s = "";
	s += x[0];
	s += x[1];
	return s;
}

string getngay(string x)
{
	string s = "";
	s += x[0];
	s += x[1];
	return s;
}

string getthang(string x)
{
	string s = "";
	s += x[3];
	s += x[4];
	return s;
}

string getnam(string x)
{
	string s = "";
	s += x[6];
	s += x[7];
	s += x[8];
	s += x[9];
	return s;
}

bool cmp(LichThi a, LichThi b)
{
	if (a.ngaythi == b.ngaythi)
	{
		if (a.giothi == b.giothi)
		{
			return a.mamonhoc < b.mamonhoc;
		}
		else
		{
			string gioa = getgio(a.giothi);
			string giob = getgio(b.giothi);
			string phuta = getphut(a.giothi);
			string phutb = getphut(b.giothi);
			if (gioa == giob)
			{
				return phuta < phutb;
			}
			else
			{
				return gioa < giob;
			}
		}
	}
	else
	{
		string ngaya = getngay(a.ngaythi);
		string thanga = getthang(a.ngaythi);
		string nama = getnam(a.ngaythi);
		string ngayb = getngay(b.ngaythi);
		string thangb = getthang(b.ngaythi);
		string namb = getnam(b.ngaythi);
		if (nama == namb)
		{
			if (thanga == thangb)
			{
				return ngaya < ngayb;
			}
			else
			{
				return thanga < thangb;
			}
		}
		else
		{
			return nama < namb;
		}
	}
}

void process(MonHoc tl[], int n, LichThi p[], int m)
{
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			if ((tl + j)->ma == (p + i)->mamonhoc)
			{
				(p + i)->tenmonhoc = (tl + j)->name;
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
	MonHoc mh[100];
	LichThi lt[1000];
	for (int i = 0; i < n; i++)
	{
		cin >> mh[i];
	}
	for (int i = 0; i < m; i++)
	{
		cin >> lt[i];
	}
	process(mh, n, lt, m);
	for (int i = 0; i < m; i++)
	{
		cout << lt[i];
	}
}
