#include<bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,m,x;
		cin>>n>>m;
		map <int,int> a;
		vector <int> c,d;
		for(int i=0;i<n;i++){
			cin>>x;
			a[x]++;
			if(a[x]==1) c.push_back(x);
		}
		for(int i=0;i<m;i++){
			cin>>x;
			if(a[x]==0) c.push_back(x);
			if(a[x]>0) d.push_back(x);
		}
		sort(c.begin(),c.end());
		sort(d.begin(),d.end());
		for(int i=0;i<c.size();i++) cout<<c[i]<<" ";
		cout<<endl;
		for(int i=0;i<d.size();i++) cout<<d[i]<<" ";
		cout<<endl;
	}
}
