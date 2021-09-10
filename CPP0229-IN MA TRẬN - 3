#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,m,i,j;
		cin>>n>>m;
		vector < vector <int> > a(n, vector <int> (m));
		for(i=0;i<n;i++){
			for(j=0;j<m;j++){
				cin>>a[i][j];
			}
		}
		i=j=0;
		cout<<a[0][0]<<" ";
		while(i<n&&j<m){
			if(j!=m-1) j++;
			else i++;
			int ii=i,jj=j;
			while(ii<n&&jj>=0){
				cout<<a[ii][jj]<<" ";
				ii++;jj--;
			}
			ii--;jj++;
			if(ii!=n-1) ii++;
			else jj++;
			if(ii==n-1&&jj==n-1){
				cout<<a[ii][jj];
				break;
			}
			while(ii>=0&&jj<m){
				cout<<a[ii][jj]<<" ";
				ii--;jj++;
			}
			i=ii+1;j=jj-1;
		}
		cout<<endl;
	}
}
