#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		long long n,k;
		cin>>n>>k;
		long long h=n/k;
		h=(k-1)*k*h/2;
		n%=k;
		h+=(n+1)*n/2;
		if(h==k) cout<<1<<endl;
		else cout<<0<<endl;
	}
}
