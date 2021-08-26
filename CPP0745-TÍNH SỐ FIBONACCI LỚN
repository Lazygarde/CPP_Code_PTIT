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
		long long a=1,b=1,c=1000000007;
		for(int i=2;i<n;i++){
			long long k=(a+b)%c;
			b=a;
			a=k;
		}
		cout<<a<<endl;
	}
}
