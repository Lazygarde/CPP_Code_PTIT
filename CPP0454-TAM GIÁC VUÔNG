#include <bits/stdc++.h>
using namespace std;
long long tes(long long a,long long b){
	long long c=a*a+b*b;
	long long k=sqrt(c);
	if(k*k==c) return k;
	return 0;
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,ok=0;
		cin>>n;
		long long a[n];
		for(int i=0;i<n;i++) cin>>a[i];
		sort(a,a+n);
		for(int i=0;i<n-2;i++){
			for(int j=i+1;j<n-1;j++){
				long long k=tes(a[i],a[j]);
				if(k!=0&&binary_search(a+j+1,a+n,k)){
					ok=1;
					break;
				}
			}
			if(ok==1) break;
		}
		if(ok==1) cout<<"YES"<<endl;
		else cout<<"NO"<<endl;
	}
}
