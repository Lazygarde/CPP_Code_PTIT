#include<bits/stdc++.h>
using namespace std;
struct data{
	int x;
	int ii;
};
bool cmp(data a,data b){
	if(a.x==b.x) return a.ii<b.ii;
	return a.x<b.x;
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,s=0;
		cin>>n;
		vector <data> a(n);
		vector <int> b(n,0);
		for(int i=0;i<n;i++){
			cin>>a[i].x;
			a[i].ii=i;
		}
		sort(a.begin(),a.end(),cmp);
		for(int i=0;i<n;i++){
			if(b[i]||a[i].ii==i) continue;
			int k=0,j=i;
			while(!b[j]){
				b[j]=1;
				j=a[j].ii;
				k++;
			}
			if(k>0) s+=k-1;
		}
		cout<<s<<endl;
	}
}
