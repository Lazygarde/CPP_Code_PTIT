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
		long long a[n],s=-1e18;
		for(int i=0;i<n;i++) cin>>a[i];
		for(int i=0;i<n;i++){
			long long k=1;
			for(int j=i;j<n;j++){
				k*=a[j];
				if(k>s) s=k;
			}
		}
		cout<<s<<endl;
	}
}
