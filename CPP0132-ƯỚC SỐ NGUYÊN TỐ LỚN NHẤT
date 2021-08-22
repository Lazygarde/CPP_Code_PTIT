#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		long long n,s;
		cin>>n;
		for(int i=2;i<=sqrt(n);i++){
			while(n%i==0){
				s=i;
				n/=i;
			}
		}
		if(n>1) s=n;
		cout<<s<<endl;
	}
}
