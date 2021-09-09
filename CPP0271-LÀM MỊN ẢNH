#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,m,l;
		long long s=0;
		cin>>n>>m>>l;
		vector < vector <int> > a(n+1, vector <int> (m+1,0));
		for(int i=1;i<=n;i++){
			for(int j=1;j<=m;j++){
				cin>>a[i][j];
				a[i][j]+=a[i-1][j]+a[i][j-1]-a[i-1][j-1];
			}
		}
		for(int i=1;i<=n-l+1;i++){
			for(int j=1;j<=m-l+1;j++){
				cout<<(a[i+l-1][j+l-1]-a[i-1][j+l-1]-a[i+l-1][j-1]+a[i-1][j-1])/(l*l)<<" ";
			}
			cout<<endl;
		}
	}
}
