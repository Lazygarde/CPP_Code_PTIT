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
		cin>>a;
		int n=a.size();		
		int s=0;
		if(a[n-1]=='1') s=1;
		for(int i=n-2;i>=0;i--){
			if(a[i]=='1'){
				if((n-i-1)%4==1) s+=2;
				else if((n-i-1)%4==2) s+=4;
				else if((n-i-1)%4==3) s+=8;
				else if((n-i-1)%4==0) s+=6;
			}
		}
		if(s%5==0) cout<<"Yes\n";
		else cout<<"No\n";
	}
}
