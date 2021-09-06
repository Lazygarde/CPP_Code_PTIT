#include <bits/stdc++.h>
using namespace std;
struct data{
	string ten;
	int ng,th,na;
};
bool cmp(data a,data b){
	if(a.na==b.na){
		if(a.th==b.th) return a.ng>b.ng;
		return a.th>b.th;
	}
	return a.na>b.na;
}
int main(){
	int n;
	cin>>n;
	struct data a[n];
	for(int i=0;i<n;i++){
		cin>>a[i].ten;
		string x;
		cin>>x;
		a[i].ng=(x[0]-'0')*10+x[1]-'0';
		a[i].th=(x[3]-'0')*10+x[4]-'0';
		a[i].na=(x[6]-'0')*1000+(x[7]-'0')*100+(x[8]-'0')*10+x[9]-'0';
	}
	sort(a,a+n,cmp);
	cout<<a[0].ten<<endl<<a[n-1].ten;
}
