#include <bits/stdc++.h>
using namespace std;
struct data{
	string masv,ten,lop;
	float d1,d2,d3;
};
bool cmp(data a,data b){
	return a.masv<b.masv;
}
int main(){
	int n;
	cin>>n;
	struct data a[n];
	for(int i=0;i<n;i++){
		cin.ignore();
		getline(cin,a[i].masv);
		getline(cin,a[i].ten);
		getline(cin,a[i].lop);
		cin>>a[i].d1>>a[i].d2>>a[i].d3;
	}
	sort(a,a+n,cmp);
	for(int i=0;i<n;i++){
		cout<<i+1<<" "<<a[i].masv<<" "<<a[i].ten<<" "<<a[i].lop;
		printf(" %.1f %.1f %.1f\n",a[i].d1,a[i].d2,a[i].d3);
	}
}
