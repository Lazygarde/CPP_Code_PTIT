#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		int n=a.size(),s=1;
		for(int i=1;i<n;i++){
			if(a[i]!=a[i-1]){
				cout<<a[i-1]<<s;
				s=1;
			}
			else s++;
		}
		cout<<a[n-1]<<s;
		cout<<endl;
	}
}
