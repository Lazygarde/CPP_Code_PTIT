#include <bits/stdc++.h>
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	string a,x="";
	getline(cin,a);
	vector <string> c;
	for(int i=0;i<a.size();i++){
		if(a[i]==' '&&a[i-1]==' ') continue;
		if(a[i]==' '){
			c.push_back(x);
			x="";
		}
		else{
			if(a[i]>='A'&&a[i]<='Z') a[i]+=32;
			x=x+a[i];
		}
	}
	c.push_back(x);
	int n=c.size();
	for(int i=0;i<n-1;i++) c[i][0]-=32;
	cout<<c[0];
	for(int i=1;i<n-1;i++) cout<<" "<<c[i];
	cout<<", ";
	for(int i=0;i<c[n-1].size();i++) cout<<(char)(c[n-1][i]-32);
}
