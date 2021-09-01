#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		long long x,s=0,maxx=0,ss=-1e9;
		for(int i=0;i<n;i++){
			cin>>x;
			s+=x;
			if(s<0) s=0;
			ss=max(x,ss);
			maxx=max(maxx,s);
		}
		if(maxx==0) maxx=ss;
		cout<<maxx<<endl;
	}
}
