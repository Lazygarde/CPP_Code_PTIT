#include <bits/stdc++.h>
using namespace std;
struct data{
	int stt;
	string masv,ten,lop,email,dn;
};
bool cmp(data a,data b){
	return a.ten<b.ten;
}
int main(){
	int n,m;
	cin>>n;
	struct data a[n];
	string x;
	cin.ignore();
	for(int i=0;i<n;i++){
		a[i].stt=i+1;
		getline(cin,a[i].masv);
		getline(cin,a[i].ten);
		getline(cin,a[i].lop);
		getline(cin,a[i].email);
		getline(cin,a[i].dn);
	}
	sort(a,a+n,cmp);
	cin>>m;
	for(int ii=0;ii<m;ii++){
		cin>>x;
		for(int i=0;i<n;i++){
			if(a[i].dn==x) cout<<a[i].stt<<" "<<a[i].masv<<" "<<a[i].ten<<" "<<a[i].lop<<" "<<a[i].email<<" "<<a[i].dn<<endl;
		}
	}
}
