#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		int a[n],l[n],s=0;
		for(int i=0;i<n;i++) cin>>a[i];
		for(int i=0;i<n;i++){
			l[i]=1;
			for(int j=0;j<i;j++){
				if(a[j]<a[i]&&l[i]<l[j]+1) l[i]=l[j]+1;
			}
			if(l[i]>s) s=l[i];
		}
		cout<<s<<endl;
	}
}
