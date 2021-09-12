#include <bits/stdc++.h>
#define a() a
using namespace std;
class SinhVien{
	public:
	string masv,ten,lop,ns;
	float gpa;
	friend istream &operator>>(istream &input,SinhVien &a){
		getline(cin,a.ten);
		cin>>a.lop>>a.ns>>a.gpa;
		a.masv="B20DCCN001";
		if(a.ns[1]=='/') a.ns="0"+a.ns;
		if(a.ns[4]=='/') a.ns.insert(a.ns.begin()+3,'0');
		return input;
	}
	friend ostream &operator<<(ostream &output,SinhVien a){
		cout<<a.masv<<" "<<a.ten<<" "<<a.lop<<" "<<a.ns;
    	printf(" %.2f",a.gpa);
		return output;
	}
};
int main(){
    SinhVien a();
    cin >> a;
    cout << a;
    return 0;
}
