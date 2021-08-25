#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,s=1e9;
		cin>>n;
		int a[n];
		for(int i=0;i<n;i++) cin>>a[i];
		sort(a,a+n);
		for(int i=1;i<n;i++){
			if(a[i]-a[i-1]<s) s=a[i]-a[i-1];
		}
		cout<<s<<endl;
	}
}
