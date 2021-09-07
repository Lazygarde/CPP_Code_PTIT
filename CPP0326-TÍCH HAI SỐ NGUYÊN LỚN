#include<bits/stdc++.h>
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
string nhanNho(char a,string b){
    string s="";
    int temp=0;
    for(int i=b.length()-1;i>=0;i--){
        temp=(a-48)*(b[i]-48)+temp;
        s.insert(0,1,(temp%10+48));
        temp=temp/10;
    }
    if (temp>0){
        s.insert(0,1,(temp+48));
    } 
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
	int t;
	cin>>t;
	while(t--){
		string a,b;
		cin>>a>>b;
		cout<<nhan(a,b)<<endl;
	}
}
