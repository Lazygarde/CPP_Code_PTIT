#include <bits/stdc++.h>
using namespace std;
struct data{
	int m,s;
};
bool cmp(data a,data b){
	if(a.s==b.s) return a.m<b.m;
	return a.s>b.s;
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,x;
		cin>>n;
		vector <data> a;
		for(int i=0;i<n;i++){
			cin>>x;
			int ok=0;
			for(int j=0;j<a.size();j++){
				if(a[j].m==x){
					ok=1;
					a[j].s++;
				}
			}
			if(ok==0){
				struct data b;
				b.m=x;
				b.s=1;
				a.push_back(b);
			}
		}
		sort(a.begin(),a.end(),cmp);
		for(int i=0;i<a.size();i++){
			for(int j=0;j<a[i].s;j++) cout<<a[i].m<<" ";
		}
		cout<<endl;
	}
}
