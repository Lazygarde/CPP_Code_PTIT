#include <bits/stdc++.h>
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	string a,b,x="";
	getline(cin,a);
	cin>>b;
	vector <string> c;
	for(int i=0;i<a.size();i++){
		if(a[i]==' '){
			c.push_back(x);
			x="";
		}
		else{
			x=x+a[i];
		}
	}
	c.push_back(x);
	for(int i=0;i<c.size();i++){
		if(c[i]!=b) cout<<c[i]<<" ";
	}
}
