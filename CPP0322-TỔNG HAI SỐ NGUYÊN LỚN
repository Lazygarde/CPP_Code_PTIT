#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
string cong(string a,string b){
	string s="";
	if(a.size()>b.size()) b.insert(0,a.size()-b.size(),'0');
	else if(a.size()<b.size()) a.insert(0,b.size()-a.size(),'0');
	int tmp=0;
    for(int i=a.size()-1;i>=0;i--){
        tmp=a[i]+b[i]-96+tmp;
        s.insert(0,1,tmp%10+48);
        tmp=tmp/10;
    }
    if(tmp>0) s.insert(0,1,tmp+48);
    return s;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string a,b;
		cin>>a>>b;
		cout<<cong(a,b)<<endl;
	}
}
