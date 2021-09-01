#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		long long a[n];
		for(int i=0;i<n;i++) cin>>a[i];
		if(n==1) cout<<a[0];
		else if(n==2) cout<<max(a[0],a[1]);
		else{
			long long b=a[0],c=a[1],d=a[2]+a[0];
			for(int i=3;i<n;i++){
				long long e=a[i];
				if(b>c) e+=b;
				else e+=c;
				b=c;c=d;d=e;
			}
			if(d>c) cout<<d;
			else cout<<c;
		}
		cout<<endl; 
	}
}
