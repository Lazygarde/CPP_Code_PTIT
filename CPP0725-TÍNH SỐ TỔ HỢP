#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
long long power(long long x, long long y, long long p){
    long long res = 1;
	while(y>0){
        if(y&1) res=(res*x)%p;
        y=y>>1;
        x=(x*x)%p;
    }
    return res;
}
long long mod(long long n,long long p){
    return power(n,p-2,p);
}
long long nCr(long long n, long long r, long long p){
    if(n<r) return 0;
    if(r==0) return 1;
    long long a[n+1];
    a[0]=1;
    for(int i=1;i<=n;i++) a[i]=(a[i-1]*i)%p;
    return (a[n]*mod(a[r],p)%p*mod(a[n-r],p)%p)%p;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		long long a,b,c=1e9+7;
		cin>>a>>b;
		cout<<nCr(a,b,c)<<endl;
	}
}
