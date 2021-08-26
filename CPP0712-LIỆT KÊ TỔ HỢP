#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,k;
		cin>>n>>k;
		int a[k];
		for(int i=0;i<k;i++) a[i]=i+1;
		while(1){
			int ok=0;
			for(int i=0;i<k;i++) cout<<a[i];
			cout<<" ";
			for(int i=k-1;i>=0;i--){
				if(a[i]!=n-k+i+1){
					ok=1;
					a[i]++;
					for(int j=i+1;j<k;j++) a[j]=a[j-1]+1;
					break;
				}
			}
			if(ok==0) break;
		}
		cout<<endl;
	}
}
