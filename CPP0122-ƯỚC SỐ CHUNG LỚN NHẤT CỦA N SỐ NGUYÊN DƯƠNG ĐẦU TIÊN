#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
long long bcnn(long long a, long long b){
	long long k=a*b;
	while(b!=0){
        long long x=a%b;
        a=b;
        b=x;
    }
    return k/a;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		long long n,s=1;
		cin>>n;
		for(int i=1;i<=n;i++) s=bcnn(s,i);
		cout<<s<<endl;
	}
}
