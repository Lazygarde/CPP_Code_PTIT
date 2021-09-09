#include <bits/stdc++.h>
using namespace std;
int Do(string a,int k){
	int s=0;
	for(int i=0;i<a.size();i++){
		int n=0;
		for(int j=i;j<a.size();j++){
			n=(n*10+a[j]-'0')%k;
			if(n==0) s++;
		}
	}
	return s;
} 
int main(){ 
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		cout<<Do(a,8)-Do(a,24)<<endl;
	}
}
