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
		long long x;
		map <int,int> a;
		for(int i=0;i<n;i++){
			cin>>x;
			if(x>=0&&x<=n) a[x]++;
		}
		for(int i=0;i<n;i++){
			if(a[i]>0) cout<<i<<" ";
			else cout<<-1<<" ";
		}
		cout<<endl;
	}
}
