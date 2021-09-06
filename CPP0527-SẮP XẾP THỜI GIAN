#include<bits/stdc++.h>
using namespace std;
struct data{
	int h,m,s;
};
bool cmp(data a,data b){
	if(a.h==b.h){
		if(a.m==b.m) return a.s<b.s;
		return a.m<b.m;
	}
	return a.h<b.h;
}
int main(){
	int n;
	cin>>n;
	struct data a[n];
	for(int i=0;i<n;i++) cin>>a[i].h>>a[i].m>>a[i].s;
	sort(a,a+n,cmp);
	for(int i=0;i<n;i++) cout<<a[i].h<<" "<<a[i].m<<" "<<a[i].s<<endl;
}
