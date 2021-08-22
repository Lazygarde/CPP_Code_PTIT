#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,s=1e6+5;
		cin>>n;
		int a[n],b[n];
		for(int i=0;i<n;i++) cin>>a[i];
		sort(a,a+n);
		for(int i=0;i<n;i+=2){
			b[i+1]=a[i/2];
			b[i]=a[n-i/2-1];
		}
		for(int i=0;i<n;i++) cout<<b[i]<<" ";
		cout<<endl;
	}
}
