#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,s=1e7,ss=1e8;
		cin>>n;
		int a[n];
		for(int i=0;i<n;i++){
			cin>>a[i];
			if(s>a[i]) s=a[i];
		}
		for(int i=0;i<n;i++){
			if(ss>a[i]&&a[i]>s) ss=a[i];
		}
		if(ss==1e8) cout<<-1<<endl;
		else cout<<s<<" "<<ss<<endl;
	}
}
