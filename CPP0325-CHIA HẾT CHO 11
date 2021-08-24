#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int chiadu(string a,int b){
	int du=0;
    for(int i=0;i<a.size();i++)
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
		cin>>a;
		if(chiadu(a,11)==0) cout<<1<<endl;
		else cout<<0<<endl;
	}
}
