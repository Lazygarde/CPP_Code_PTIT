#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,k,l,r;
		cin>>n>>k;
		int a[n+1];a[0]=0;
		for(int i=1;i<=n;i++){
			cin>>a[i];
			a[i]+=a[i-1];
		}
		while(k--){
			cin>>l>>r;
			cout<<a[r]-a[l-1]<<endl;
		}
	}
}
