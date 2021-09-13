#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		int a[n];
		vector <int> b(n,1),c(n,1);
		for(int i=0;i<n;i++) cin>>a[i];
		for(int i=1;i<n;i++){
			for(int j=0;j<i;j++){
				if(a[i]>a[j]&&b[i]<b[j]+1) b[i]=b[i]+1;
			}
		}
		for(int i=n-2;i>=0;i--){
			for(int j=n-1;j>i;j--){
				if(a[i]>a[j]&&c[i]<c[j]+1) c[i]=c[j]+1;
			}
		}
		int s=b[0]+c[0]-1;
		for(int i=1;i<n;i++) s=max(s,b[i]+c[i]-1);
		cout<<s<<endl;
	}
}
