#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
long long chiadu(string a,long long b){
	long long du=0;
    for(int i=0;i<a.length();i++)
        du=(du*10+a[i]-48)%b;
    return du;
}
string cong(string a,string b){
	int ok=0;
	string s="";
	if(a.size()>b.size()) b.insert(0,a.size()-b.size(),'0');
	else if(a.size()<b.size()) a.insert(0,b.size()-a.size(),'0');
	int temp = 0;
    for(int i=a.size()-1; i>=0; i--) {
        temp=a[i]+b[i]-96+temp;
        s.insert(0,1,temp%10+48);
        temp = temp/10;
    }
    if(temp>0) s.insert(0,1,temp+48);
    return s;
}
string nhanNho(char a,string b){
    string s="";
    int temp=0;
    for(int i=b.length()-1;i>=0;i--){
        temp=(a-48)*(b[i]-48)+temp;
        s.insert(0,1,(temp%10+48));
        temp=temp/10;
    }
    if(temp>0) s.insert(0,1,(temp+48));
    return s;
}
string nhan(string a, string b){
    string s="";
    int l=a.length();
    string s1[l];
    for(int i=l-1;i>=0;i--){
        s1[i]=nhanNho(a[i],b);
        s1[i].insert(s1[i].length(),l-i-1,'0');   
        s=cong(s,s1[i]);
    }
    return s;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string a,b;
		long long c;
		cin>>a>>b>>c;
		string s=nhan(a,b);
		cout<<chiadu(s,c)<<endl;
	}
}
