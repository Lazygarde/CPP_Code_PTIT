#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
long long ucln(long long a, long long b) {
    while(b!=0){
        long long x=a%b;
        a=b;
        b=x;
    }
    return a;
}
int main(){
    ios_base::sync_with_stdio(0);
    cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		long long n,x,y;
		cin>>n>>x>>y;
		long long k=ucln(x,y);
		for(int i=0;i<k;i++) cout<<n;
		cout<<endl;
	}
}
