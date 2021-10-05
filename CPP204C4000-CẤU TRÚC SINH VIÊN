#include <bits/stdc++.h>
using namespace std;
struct SinhVien{
	string ten,ma,ns;
	float gpa;
};
void nhapThongTinSV(struct SinhVien &a){
	getline(cin,a.ten);
	cin>>a.ma>>a.ns>>a.gpa;
	if(a.ns[1]=='/') a.ns.insert(0,1,'0');
	if(a.ns[4]=='/') a.ns.insert(3,1,'0');
}
void inThongTinSV(struct SinhVien a){
	cout<<"N20DCCN001 "<<a.ten<<" "<<" "<<a.ma<<" "<<a.ns;
	printf(" %.2f",a.gpa);
}
int main(){
    struct SinhVien a;
    nhapThongTinSV(a);
    inThongTinSV(a);
    return 0;
}
