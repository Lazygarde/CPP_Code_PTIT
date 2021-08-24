#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string a;
		int k,s=0,b[26]={};
		cin>>a>>k;
		for(int i=0;i<a.size();i++){
			b[a[i]-'a']++;
		}
		for(int i=0;i<26;i++){
			if(b[i]==0) s++;
		}
		if(s<=k) cout<<1<<endl;
		else cout<<0<<endl;
	}
}
