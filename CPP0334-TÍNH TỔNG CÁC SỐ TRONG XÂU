#include<bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		int n=a.size(),s=0,ss=0;
		for(int i=0;i<n;i++){
			if(a[i]<'0'||a[i]>'9'){
				s+=ss;
				ss=0;
			}
			else ss=ss*10+a[i]-'0';
		}
		s+=ss;
		cout<<s<<endl;
	}
}
