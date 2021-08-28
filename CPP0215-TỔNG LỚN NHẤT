#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,m;
		cin>>n>>m;
		long long a[n+1],b[m+1],s,x;
		a[0]=b[0]=0;
		for(int i=1;i<=n;i++){
			cin>>x;
			a[i]=a[i-1]+x;
		}
		for(int i=1;i<=m;i++){
			cin>>x;
			b[i]=b[i-1]+x;
		}
		s=max(a[n],b[m]);
		for(int i=1;i<=min(m,n);i++) s=max(s,max(a[i]+b[m]-b[i],b[i]+a[n]-a[i]));
		cout<<s<<endl;
	}
}
