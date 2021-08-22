#include <bits/stdc++.h>
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
 	int t;
 	cin>>t;
 	while(t--){
 		int n;
 		long long k;
 		cin>>n>>k;
 		map <long long,long long> b;
 		long long a[n];
 		long long s=0;
 		for(int i=0;i<n;i++){
 			cin>>a[i];
 			b[a[i]]++;
		}
		for(int i=0;i<n;i++){
			if(b[k-a[i]]>0){
				if(a[i]==k-a[i]) s+=b[k-a[i]]-1;
				else s+=b[k-a[i]];
			}
		}
		cout<<s/2<<endl;
	}
}
