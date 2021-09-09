#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,m;
		long long s=0;
		cin>>n>>m;
		int a[n][m],b[3][3];
		for(int i=0;i<n;i++){
			for(int j=0;j<m;j++){
				cin>>a[i][j];
			}
		}
		for(int i=0;i<3;i++) cin>>b[i][0]>>b[i][1]>>b[i][2];
		for(int i=0;i<n-2;i++){
			for(int j=0;j<m-2;j++){
				for(int ii=i;ii<i+3;ii++){
					for(int jj=j;jj<j+3;jj++){
						s+=a[ii][jj]*b[ii-i][jj-j];
					}
				}
			}
		}
		cout<<s<<endl;
	}
}
