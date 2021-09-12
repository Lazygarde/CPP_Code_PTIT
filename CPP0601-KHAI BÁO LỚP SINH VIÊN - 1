#include <bits/stdc++.h>
#define a() a
using namespace std;
class SinhVien{
	public:
	string masv,ten,lop,ns;
	float gpa;
};
void nhap(SinhVien &a){
	getline(cin,a.ten);
	cin>>a.lop>>a.ns>>a.gpa;
	a.masv="B20DCCN001";
	if(a.ns[1]=='/') a.ns="0"+a.ns;
	if(a.ns[4]=='/') a.ns.insert(a.ns.begin()+3,'0');
}
void in(SinhVien a){
	cout<<a.masv<<" Nguyen Van A "<<a.lop<<" "<<a.ns;
	printf(" %.2f",a.gpa);
}
int main(){
    SinhVien a();
    nhap(a);
    in(a);
    return 0;
}
