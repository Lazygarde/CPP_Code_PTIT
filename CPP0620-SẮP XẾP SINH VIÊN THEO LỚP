#include <bits/stdc++.h>
using namespace std;
struct data{
	string masv,ten,lop,mail;
};
bool cmp(data a,data b){
	if(a.lop==b.lop) return a.masv<b.masv;
	return a.lop<b.lop;
}
int main() {
    int n;
    cin>>n;
    struct data a[n];
    for(int i=0;i<n;i++){
    	cin>>a[i].masv;
    	cin.ignore();
    	getline(cin,a[i].ten);
    	cin>>a[i].lop>>a[i].mail;
	}
	sort(a,a+n,cmp);
	for(int i=0;i<n;i++) cout<<a[i].masv<<" "<<a[i].ten<<" "<<a[i].lop<<" "<<a[i].mail<<endl;
}
