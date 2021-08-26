#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		long long n,k,s=0;
		cin>>n>>k;
		long long a[n],h=1;
		for(int i=0;i<n;i++) cin>>a[i];
		for(int i=n-1;i>=0;i--){
			s=(s+h*a[i])%1000000007;
			h=(h*k)%1000000007;
		}
		cout<<s<<endl;
	}
}
