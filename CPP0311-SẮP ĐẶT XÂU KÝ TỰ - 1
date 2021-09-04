#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		int n=a.size(),b[26]={},s=0;
		for(int i=0;i<n;i++){
			b[a[i]-'a']++;
			s=max(s,b[a[i]-'a']);
		}
		if(s<=(a.size()+1)/2) cout<<1<<endl;
		else cout<<0<<endl;
	}
}
