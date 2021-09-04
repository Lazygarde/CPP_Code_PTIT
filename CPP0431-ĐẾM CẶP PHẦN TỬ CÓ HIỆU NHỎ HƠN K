#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
	    long long s=0;
		int n,k;
		cin>>n>>k;
		vector <int> a(n);
		for(int i=0;i<n;i++) cin>>a[i];
		sort(a.begin(),a.end());
		for(int i=0;i<n-1;i++){
			int x=lower_bound(a.begin()+i+1,a.end(),a[i]+k)-a.begin();
			if(x==n) x--;
			if(a[x]>a[i]+k) x--;
			while(a[x]==a[i]+k) x--;
			if(x>i) s+=x-i;
		}
		cout<<s<<endl;
	}
}
