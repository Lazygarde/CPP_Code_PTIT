#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,m;
		cin>>n>>m;
		long long x,maxx=-1e8,minn=1e8;
		for(int i=0;i<n;i++){
			cin>>x;
			if(maxx<x) maxx=x;
		}
		for(int i=0;i<m;i++){
			cin>>x;
			if(minn>x) minn=x;
		}
		cout<<minn*maxx<<endl;
	}
}
