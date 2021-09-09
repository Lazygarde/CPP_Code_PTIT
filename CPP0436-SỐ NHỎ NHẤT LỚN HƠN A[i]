#include <bits/stdc++.h>
using namespace std;
int main(){ 
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		int a[n],b[n+1];b[n]=1e9;
		for(int i=0;i<n;i++){
			cin>>a[i];
			b[i]=a[i];
		}
		sort(b,b+n);
		for(int i=0;i<n;i++){
			int k=upper_bound(b,b+n+1,a[i])-b;
			if(k==n) cout<<"_ ";
			else cout<<b[k]<<" ";
		}
		cout<<endl;
	}
}
