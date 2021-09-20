#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,r,g,b;
		cin>>n>>r>>b>>g;
		int l=n-(r+g+b);
		long long a[n+1],s=0;
		a[0]=1;
		for(int i=1;i<=n;i++) a[i]=a[i-1]*i;
		for(int i=0;i<=l;i++){
			for(int j=0;j<=l-i;j++){
				int k=l-i-j;
				s=s+a[n]/(a[i+r]*a[j+b]*a[k+g]);
			}
		}
		cout<<s<<endl;
	}
}
