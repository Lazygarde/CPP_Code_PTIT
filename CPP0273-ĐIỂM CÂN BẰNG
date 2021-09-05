#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,s=0,ss=0,ok=-1;
		cin>>n;
		int a[n];
		for(int i=0;i<n;i++){
			cin>>a[i];
			s+=a[i];
		}
		for(int i=0;i<n;i++){
			if(ss*2==s-a[i]){
				ok=i+1;
				break;
			}
			ss+=a[i];
		}
		cout<<ok<<endl;
	}
}
