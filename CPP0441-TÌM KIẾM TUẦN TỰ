#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,x,k,ok=0;
		cin>>n>>k;
		for(int i=0;i<n;i++){
			cin>>x;
			if(x==k&&ok==0) ok=i+1;
		}
		if(ok==0) cout<<-1<<endl;
		else cout<<ok<<endl;
	}
}
