#include <bits/stdc++.h>
using namespace std;
int main(){
	int n,k,b,x,s=1e9,ss=0;
	cin>>n>>k>>b;
	vector <int> a(n+1,1);
	for(int i=0;i<b;i++){
		cin>>x;
		a[x]=0;
	}
	for(int i=1;i<=k;i++) ss+=a[i];
	s=min(s,k-ss);
	for(int i=k+1;i<=n;i++){
		ss=ss+a[i]-a[i-k];
		s=min(s,k-ss);
	}
	cout<<s;
}
