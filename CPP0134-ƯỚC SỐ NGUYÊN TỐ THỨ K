#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int nto(int n){
	if(n<2) return 0;
	for(int i=2;i<=sqrt(n);i++){
		if(n%i==0) return 0;
	}
	return 1;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,k,ok=0;
		cin>>n>>k;
		for(int i=2;i<=sqrt(n);i++){
			while(n%i==0){
				k--;
				n/=i;
				if(k==0){
					ok=1;
					cout<<i;
					break;
				}
			}
		}
		if(n>1&&k==1) cout<<n;
		else if(ok==0) cout<<-1;
		cout<<endl;
	}
}
