#include<bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,m,s=-1e9;
		cin>>n>>m;
		int a[n][m];
		for(int i=0;i<n;i++){
			for(int j=0;j<m;j++){
				cin>>a[i][j];
			}
		}
		for(int i=0;i<m;i++){
			vector <int> b(n,0);
			for(int j=i;j<m;j++){
				int h=0;
				for(int k=0;k<n;k++){
					b[k]+=a[k][j];
					h=max(b[k],b[k]+h);
					s=max(s,h);
				}
			}
		}
		cout<<s<<endl;
	}
}
