#include <bits/stdc++.h>
using namespace std;
struct data{
	string ten,mon,ma,tt,s;
};
void chuanhoa(string &a){
	string x="";
	x+=a[0];
	for(int i=0;i<a.size();i++){
    	if(a[i]==' ') x+=(char)(a[i+1]-32);
	}
	a=x;
}
int main(){
    int n;
    cin>>n;
    struct data a[n];
    cin.ignore();
    for(int i=0;i<n;i++){
    	getline(cin,a[i].ten);
    	getline(cin,a[i].mon);
    	if(i<9) a[i].ma="GV0";
    	else a[i].ma="GV";
    	a[i].ma+=to_string(i+1);
    	int m=a[i].ten.size(),k;
    	a[i].tt="";
    	a[i].s="";
    	for(int j=0;j<a[i].ten.size();j++){
    		char k=a[i].ten[j];
    		if(k>='A'&&k<='Z') k+=32;
    		a[i].s+=k;
		}
    	chuanhoa(a[i].mon);
    	for(int j=m-1;j>=0;j--){
    		if(a[i].ten[j]==' '){
    			k=j;
    			break;
			}
		}
		for(int j=k+1;j<m;j++) a[i].tt+=a[i].ten[j];
	}
	int t;
	cin>>t;
	cin.ignore();
	while(t--){
		string x;
		getline(cin,x);
		cout<<"DANH SACH GIANG VIEN THEO TU KHOA "<<x<<":"<<endl;
		string k="";
		for(int i=0;i<x.size();i++){
			k+=x[i];
			if(k[i]>='A'&&k[i]<='Z') k[i]+=32;
		}
		for(int i=0;i<n;i++){
			if(a[i].s.find(k)!=-1) cout<<a[i].ma<<" "<<a[i].ten<<" "<<a[i].mon<<endl;
		}
	}
}
