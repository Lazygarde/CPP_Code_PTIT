#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		long long n,a=1,b=1;
		cin>>n;
		if(n<=3){
			cout<<"YES"<<endl;
			continue;
		}
		while(a<n){
			long long k=a+b;
			b=a;
			a=k;
		}
		if(a==n) cout<<"YES"<<endl;
		else cout<<"NO"<<endl;
	}
}
