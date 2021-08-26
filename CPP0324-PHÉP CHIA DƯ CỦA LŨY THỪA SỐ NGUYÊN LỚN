#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
long long chiadu(string a,long long b){
	long long du=0;
    for(int i=0;i<a.length();i++)
        du=(du*10+a[i]-48)%b;
    return du;
}
long long poww(long long n,long long k,long long mod){
	if(k==1) return n;
	long long x=poww(n,k/2,mod);
	if(k%2==0) return (x*x)%mod;
	else return (((x*x)%mod)*n)%mod;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string a;
		long long b,m;
		cin>>a>>b>>m;
		long long k=chiadu(a,m);
		cout<<poww(k,b,m)<<endl;
	}
}
