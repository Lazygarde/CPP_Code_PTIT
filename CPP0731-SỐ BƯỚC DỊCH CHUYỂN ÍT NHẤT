#include <bits/stdc++.h>
using namespace std;
int a[1005];
int Do(int n){
	int b[n],s;
	b[n-1]=0;
	for(int i=n-2;i>=0;i--){
		if(a[i]==0) b[i]=1e9;
		else if(a[i]>=n-i-1) b[i]=1;
		else{
			s=1e9;
			for(int j=i+1;j<n&&j<=a[i]+i;j++) s=min(s,b[j]);
			if(s!=1e9) b[i]=s+1;
			else b[i]=s;
		}
	}
	return b[0];
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		for(int i=0;i<n;i++) cin>>a[i];
		cout<<Do(n)<<endl;
	}
}
