#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		int s=0;
		for(int i=0;i<a.size();i++) s+=a[i]-'0';
		while(s>9){
			int k=s,ss=0;
			while(k!=0){
				ss+=k%10;
				k/=10;
			}
			s=ss;
		}
		if(s==9) cout<<1<<endl;
		else cout<<0<<endl;
	}
}
