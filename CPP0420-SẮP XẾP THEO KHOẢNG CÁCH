#include <bits/stdc++.h>
using namespace std;
struct data{
	int x,ii,xx;
};
bool cmp(data a,data b){
	if(a.xx==b.xx) return a.ii<b.ii;
	else return a.xx<b.xx;
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,k;
		cin>>n>>k;
		vector <data> a(n);
		for(int i=0;i<n;i++){
			cin>>a[i].x;
			a[i].ii=i;
			a[i].xx=abs(a[i].x-k);
		}
		sort(a.begin(),a.end(),cmp);
		for(int i=0;i<n;i++) cout<<a[i].x<<" ";
		cout<<endl;
	}
}
