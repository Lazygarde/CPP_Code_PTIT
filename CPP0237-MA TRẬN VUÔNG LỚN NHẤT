#include <bits/stdc++.h>
using namespace std;
char a[25][25];
bool check(int x,int y,int k){
	for(int i=x;i<x+k;i++){
		if(a[i][y]=='O'||a[i][y+k-1]=='O') return 0; 
	}
	for(int i=y;i<y+k;i++){
		if(a[x][i]=='O'||a[x+k-1][i]=='O') return 0;
	}
	return 1;
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		for(int i=0;i<n;i++){
			for(int j=0;j<n;j++){
				cin>>a[i][j];
			}
		}
		for(int k=n;k>=1;k--){
			int ok=0;
			for(int i=0;i<=n-k;i++){
				for(int j=0;j<=n-k;j++){
					if(check(i,j,k)){
						ok=1;
						break;
					}
				}
				if(ok==1) break;
			}
			if(ok==1){
				cout<<k<<endl;
				break;
			}
		}
	}
}
