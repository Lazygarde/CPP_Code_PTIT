#include <bits/stdc++.h>
using namespace std;
int n,m;
char a[25][25];
void Do(int i,int j){
	if(i<0||i>=n||j<0||j>=m) return;
	if(a[i][j]!='-') return;
    a[i][j]='O';
    Do(i+1,j);
    Do(i-1,j);
    Do(i,j+1);
    Do(i,j-1);
}
int main(){
	int t;
	cin>>t;
	while(t--){
		cin>>n>>m;
		for(int i=0;i<n;i++){
			for(int j=0;j<m;j++){
				cin>>a[i][j];
				if(a[i][j]=='O') a[i][j]='-';
			}
		}
		for(int i=0;i<n;i++){
			if(a[i][0]=='-') Do(i,0);
			if(a[i][m-1]=='-') Do(i,m-1);
		}
		for(int i=0;i<m;i++){
			if(a[0][i]=='-') Do(0,i);
			if(a[n-1][i]=='-') Do(n-1,i);
		}
		for(int i=0;i<n;i++){
			for(int j=0;j<m;j++){
				if(a[i][j]=='-') cout<<"X ";
				else cout<<a[i][j]<<" ";
			}
			cout<<endl;
		}
	}
}
