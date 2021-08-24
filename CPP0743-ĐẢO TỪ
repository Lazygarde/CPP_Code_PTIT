#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	cin.ignore();
	while(t--){
		string s,x="";
		getline(cin,s);
		int n=s.size();
		vector <string> a;
		for(int i=0;i<n;i++){
			if(s[i]==' '){
				a.push_back(x);
				x="";
			}
			else x=x+s[i];
		}
		a.push_back(x);
		n=a.size();
		for(int i=n-1;i>=0;i--) cout<<a[i]<<" ";
		cout<<endl;
	}
}
