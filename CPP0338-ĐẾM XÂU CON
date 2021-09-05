#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		string a;
		int k;
		cin>>a>>k;
		int b[26]={},n=a.size(),ss=0;
		for(int i=0;i<n;i++){
			int b[26]={},l=n,s=0,r=n;
			for(int j=i;j<n;j++){
				if(b[a[j]-'a']==0) s++;
				b[a[j]-'a']++;
				if(s==k){
					l=j;
					break;
				}
			}
			for(int j=l+1;j<n;j++){
				if(b[a[j]-'a']==0){
					r=j;
					break;
				}
			}
			if(l<=r) ss+=r-l;
		}
		cout<<ss<<endl;
	}
}
