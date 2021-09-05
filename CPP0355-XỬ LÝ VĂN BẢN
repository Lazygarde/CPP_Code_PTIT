#include<bits/stdc++.h>
using namespace std;
int main(){
	string a;
	int ok=1;
	while(cin>>a){
		int n=a.size();
		for(int i=0;i<n;i++){
			if(a[i]>='A'&&a[i]<='Z') a[i]+=32;
		}
		if(ok==1){
			a[0]-=32;
			ok=0;
		}
		if(a[n-1]=='.'||a[n-1]=='!'||a[n-1]=='?'){
			a.erase(a.end()-1);
			cout<<a<<endl;
			ok=1;
		}
		else cout<<a<<" ";
	}
}
