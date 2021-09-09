#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n;
		long long s=0;
		cin>>n;
		int a[n];
		for(int i=0;i<n;i++) cin>>a[i];
		while(1){
			int m=0;
			for(int i=0;i<n;i++){
				if(a[i]%2==1){
					a[i]--;
					s++;
				}
				if(a[i]==0) m++;
			}
			if(m==n) break;
			for(int i=0;i<n;i++) a[i]/=2;
			s++;
		}
		cout<<s<<endl;
	}
}
