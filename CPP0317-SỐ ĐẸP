#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
string dep(string a){
	int n=a.size();
	for(int i=0;i<=(n+1)/2;i++){
		if(a[i]!=a[n-i-1]||(a[i]-'0')%2==1) return "NO";
	}
	return "YES";
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		cout<<dep(a)<<endl;
	}
}
