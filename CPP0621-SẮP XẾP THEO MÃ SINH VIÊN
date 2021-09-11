#include <bits/stdc++.h>
using namespace std;
class data{
	public:
	string masv,ten,lop,mail;
	friend istream &operator>>(istream &input,data &a){ 
		cin>>a.masv;
		cin.ignore();
		getline(cin,a.ten);
		cin>>a.lop>>a.mail;
		return input;            
	}
	friend ostream &operator<<(ostream &output,data &a){ 
        cout<<a.masv<<" "<<a.ten<<" "<<a.lop<<" "<<a.mail;
        return output;            
	}
};
bool cmp(data a,data b){
	return a.masv<b.masv;
}
int main(){
	int n=0;
	data a[10000];
	while(cin>>a[n]) n++;
	sort(a,a+n,cmp);
	for(int i=0;i<n;i++) cout<<a[i]<<endl;
}
