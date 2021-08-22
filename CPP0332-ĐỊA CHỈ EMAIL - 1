#include <bits/stdc++.h>
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	string a,x="";
	getline(cin,a);
	vector <string> c;
	for(int i=0;i<a.size();i++){
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
	cout<<c[c.size()-1];
	for(int i=0;i<c.size()-1;i++) cout<<c[i][0];
	cout<<"@ptit.edu.vn";
}
