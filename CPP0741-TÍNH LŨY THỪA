#include <bits/stdc++.h>
using namespace std;
long long poww(long long n,long long k,long long p){
	if(k==1) return n;
	long long x=poww(n,k/2,p);
	if(k%2==0) return (x*x)%p;
	else return (((x*x)%p)*n)%p;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		long long x,y,p;
		cin>>x>>y>>p;
		cout<<poww(x,y,p)<<endl;
	}
}
