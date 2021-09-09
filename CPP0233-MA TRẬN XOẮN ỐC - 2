#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,m;
		cin>>n>>m;
		int a[n][m],b[n*m];
		for(int i=0;i<n;i++){
			for(int j=0;j<m;j++){
				cin>>a[i][j];
			}
		}
		int dong=n,cot=m,k=0,p=0;
		while(k<n*m){
			for(int i=p;i<cot;i++) b[k++]=a[p][i];
			for(int i=p+1;i<dong;i++) b[k++]=a[i][cot-1];
			if(p!=dong-1) for(int i=cot-2;i>=p;i--) b[k++]=a[dong-1][i];
			if(p!=cot-1) for(int i=dong-2;i>p;i--) b[k++]=a[i][p];
			p++;dong--;cot--;
		}
		for(int i=n*m-1;i>=0;i--) cout<<b[i]<<" ";
		cout<<endl;
	}
}
