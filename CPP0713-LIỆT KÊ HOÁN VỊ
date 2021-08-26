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
		int a[n];
		for(int i=0;i<n;i++) a[i]=i+1;
		while(1){
			int ok=0;
			for(int i=0;i<n;i++) cout<<a[i];
			cout<<" ";
			for(int i=n-2;i>=0;i--){
				if(a[i]<a[i+1]){
					ok=1;
					sort(a+i+1,a+n);
					for(int j=i+1;j<n;j++){
						if(a[i]<a[j]){
							swap(a[i],a[j]);
							break;
						}
					}
					break;
				}
			}
			if(ok==0) break;
		}
		cout<<endl;
	}
}
