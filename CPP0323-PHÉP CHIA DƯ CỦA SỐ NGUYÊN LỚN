#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
long long chiadu(string a,long long b){
	long long du=0;
    for(int i=0;i<a.length();i++)
        du=(du*10+a[i]-48)%b;
    return du;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string a;
		long long b;
		cin>>a>>b;
		cout<<chiadu(a,b)<<endl;
	}
}
