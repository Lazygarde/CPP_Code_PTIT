#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string x;
		long long a=0,b;
		cin>>b>>x;
		for(int i=0;i<x.size();i++){
			a=(a*10+x[i]-'0')%b;
		}
		while(b!=0){
			long long k=a%b;
			a=b;
			b=k;
		}
		cout<<a<<endl;
	}
}
