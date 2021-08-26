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
		vector <int> a;
		for(int i=2;i<=sqrt(n);i++){
			while(n%i==0){
				a.push_back(i);
				n/=i;
			}
		}
		if(n>1) a.push_back(n);
		if(a.size()==3&&a[0]!=a[1]&&a[1]!=a[2]&&a[0]!=a[2]) cout<<1<<endl;
		else cout<<0<<endl;
	}
}
