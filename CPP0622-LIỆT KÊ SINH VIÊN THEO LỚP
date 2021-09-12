#include <bits/stdc++.h>
using namespace std;
struct data{
	string masv,ten,lop,mail;
};
int main(){
    int n;
    cin>>n;
    struct data a[n];
    for(int i=0;i<n;i++){
    	cin>>a[i].masv;
    	cin.ignore();
    	getline(cin,a[i].ten);
    	cin>>a[i].lop>>a[i].mail;
	}
	int t;
	cin>>t;
	while(t--){
		string x;
		cin>>x;
		cout<<"DANH SACH SINH VIEN LOP "<<x<<":"<<endl;
		for(int i=0;i<n;i++){
			if(x==a[i].lop) cout<<a[i].masv<<" "<<a[i].ten<<" "<<a[i].lop<<" "<<a[i].mail<<endl;
		}
	}
}
