#include <bits/stdc++.h>
using namespace std;
struct data{
	string ten,mon,ma,tt,mm;
};
bool cmp(data a,data b){
	if(a.tt==b.tt) return a.ma<b.ma;
	return a.tt<b.tt;
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
    	a[i].mm="";
		a[i].mm+=a[i].mon[0];
    	for(int j=0;j<a[i].mon.size();j++){
    		if(a[i].mon[j]==' ') a[i].mm+=(char)(a[i].mon[j+1]-32);
		}
    	for(int j=m-1;j>=0;j--){
    		if(a[i].ten[j]==' '){
    			k=j;
    			break;
			}
		}
		for(int j=k+1;j<m;j++) a[i].tt+=a[i].ten[j];
	}
	sort(a,a+n,cmp);
	for(int i=0;i<n;i++) cout<<a[i].ma<<" "<<a[i].ten<<" "<<a[i].mm<<endl;
}
