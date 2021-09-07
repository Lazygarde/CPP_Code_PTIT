#include <bits/stdc++.h>
using namespace std;
long long mod=1e9+7;
long long pow1(long long n,long long m){
	if(m==1) return n;
	if(m%2==0) return (pow1(n,m/2)*pow1(n,m/2))%mod;
	else return (n*pow1(n,m-1))%mod;
}
long long ucln(long long a, long long b) {
    while(b!=0){
        long long x=a%b;
        a=b;
        b=x;
    }
    return a;
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		long long a[n];
		for(int i=0;i<n;i++) cin>>a[i];
		long long u=a[0],k=1;
		for(int i=1;i<n;i++){
			u=ucln(u,a[i]);
		}
		for(int i=0;i<n;i++){
			k*=a[i];
			k=k%mod;
		}
		k=k%mod;
		k=pow1(k,u);
		cout<<k<<endl;
	}
}
