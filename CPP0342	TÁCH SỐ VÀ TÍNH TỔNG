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
			if(a[i]>='A'&&a[i]<='Z') b[a[i]-'A']++;
			else s+=a[i]-'0';
		}
		for(int i=0;i<26;i++){
			while(b[i]>0){
				cout<<(char)(i+'A');
				b[i]--;
			}
		}
		cout<<s<<endl;
	}
}
