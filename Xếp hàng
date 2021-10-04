#include <bits/stdc++.h>
using namespace std;
struct data{
	int l,r;
};
bool cmp(data a,data b){
	if(a.l==b.l) return a.r<b.r;
	return a.l<b.l;
}
int main(){
	int n,s=0;
	cin>>n;
	struct data a[n];
	for(int i=0;i<n;i++) cin>>a[i].l>>a[i].r;
	sort(a,a+n,cmp);
	for(int i=0;i<n;i++){
		if(s<a[i].l) s=a[i].l;
		s+=a[i].r;
	}
	cout<<s;
}
