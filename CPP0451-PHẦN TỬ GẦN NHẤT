#include<bits/stdc++.h>
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);cout.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,k,x,l,r;
		cin>>n;
		vector <int> a(n);
		for(int i=0;i<n;i++) cin>>a[i];
		cin>>k>>x;
		int m=lower_bound(a.begin(),a.end(),x)-a.begin();
		if(a[m]==x){
			r=m+1;
			l=m-1;
		}
		else{
			r=m;
			l=m-1;
		}
		for(int i=k/2-1;i>=0;i--){
			cout<<a[l-i]<<" ";
		}
		for(int i=0;i<k/2;i++){
			cout<<a[r+i]<<" ";
		}
		cout<<endl;
	}
}
