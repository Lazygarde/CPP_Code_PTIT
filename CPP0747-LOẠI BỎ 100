#include <bits/stdc++.h>
using namespace std;
int main(){
	freopen("input.txt","r", stdin);
	freopen("output.txt","w",stdout);
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		int n=a.size();
		for(int i=0;i<a.size()-2;i++){
		    if(a=="") break;
			if(a[i]=='1'&&a[i+1]=='0'&&a[i+2]=='0'){
				a.erase(a.begin()+i,a.begin()+i+3);
				i-=2;
			}
		}
		cout<<n-a.size()<<endl;
	}
}
