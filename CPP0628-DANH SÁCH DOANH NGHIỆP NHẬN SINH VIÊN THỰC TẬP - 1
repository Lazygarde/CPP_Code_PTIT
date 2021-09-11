#include <bits/stdc++.h>
using namespace std;
struct data{
	string ma,ten;
	int s;
};
bool cmp(data a,data b){
	if(a.s==b.s) return a.ma<b.ma;
	return a.s>b.s;
}
int main(){
    int n;
    cin>>n;
    struct data a[n];
    for(int i=0;i<n;i++){
    	cin.ignore();
    	cin>>a[i].ma;
    	cin.ignore();
    	getline(cin,a[i].ten);
    	cin>>a[i].s;
	}
	sort(a,a+n,cmp);
	for(int i=0;i<n;i++) cout<<a[i].ma<<" "<<a[i].ten<<" "<<a[i].s<<endl;
}
