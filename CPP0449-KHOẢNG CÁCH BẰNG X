#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,k;
		cin>>n>>k;
		int a[n],s=0,ok=0;
		map <int,int> b;
		for(int i=0;i<n;i++){
			cin>>a[i];
			b[a[i]]++;
		}
		for(int i=0;i<n;i++){
			if(b[k+a[i]]){
				ok=1;
				break;
			}
		}
		if(ok==1) cout<<1<<endl;
		else cout<<-1<<endl;
	}
}
