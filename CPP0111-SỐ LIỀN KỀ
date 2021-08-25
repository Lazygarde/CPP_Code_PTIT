#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		int n=a.size(),ok=0;
		for(int i=1;i<n;i++){
			if(abs(a[i]-a[i-1])!=1){
				ok=1;
				break;
			}
		}
		if(ok==0) cout<<"YES"<<endl;
		else cout<<"NO"<<endl;
	}
}
