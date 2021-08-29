#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string s;
		cin>>s;
		vector <int> a;
		int pos=0;
		for(int i=0;i<s.size();i++){
			if(s[i]=='D'){
				if(i==0||s[i-1]=='I'){
					a.push_back(pos+1);
					pos++;
				}
				a.push_back(pos+1);
				pos++;
			}
			else{
				while(a.size()!=0){
					cout<<a[a.size()-1];
					a.erase(a.end()-1);
				}
				if(i==0){
					cout<<pos+1;
					pos++;
				}
				if(s[i+1]!='D'){
					cout<<pos+1;
					pos++;
				}
			}
		}
		while(a.size()!=0){ 
			cout<<a[a.size()-1];
			a.erase(a.end()-1);
		}
		cout<<endl;
	}
}
