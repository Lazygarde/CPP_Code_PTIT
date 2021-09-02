#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,k,s=0,mac=-1e9,l=0,r=k-1;
		cin>>n>>k;
		int a[n];
		for(int i=0;i<n;i++) cin>>a[i];
		for(int i=0;i<k;i++) s+=a[i];
		mac=max(mac,s);
		for(int i=k;i<n;i++){
			s=s+a[i]-a[i-k];
			if(mac<s){
				mac=s;
				l=i-k+1;r=i;
			}
		}
		for(int i=l;i<=r;i++) cout<<a[i]<<" ";
		cout<<endl;
	}
}
