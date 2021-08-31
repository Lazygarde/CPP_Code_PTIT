#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		int n=a.size(),ok=0;
		for(int i=n-2;i>=0;i--){
			if(a[i]>a[i+1]){
				ok=1;
				int s=0,k;
				for(int j=i+1;j<n;j++){
					if(a[j]<a[i]){
						if(a[j]>s){
							s=a[j];
							k=j;
						}
					}
				}
				swap(a[i],a[k]);
				break;
			}
		}
		if(ok==0) cout<<-1<<endl;
		else cout<<a<<endl;
	}
}
