#include <bits/stdc++.h>
using namespace std;
struct SinhVien{
	string ten,lop,ns;
	float s;
};
void nhap(struct SinhVien &a){
	getline(cin,a.ten);
	cin>>a.lop>>a.ns>>a.s;
}
void in(struct SinhVien a){
	if(a.ns[1]=='/') a.ns.insert(0,1,'0');
	if(a.ns[4]=='/') a.ns.insert(3,1,'0');
	cout<<"B20DCCN001 "<<a.ten<<" "<<a.lop<<" "<<a.ns<<" ";
	printf("%.2f",a.s);
}
int main(){
	struct SinhVien A;
    nhap(A);
    in(A);
    return 0;
}
