#include<bits/stdc++.h>
using namespace std;
int x,y,z,t,n,m;
bool a[2005][2005];
struct data{
	int x,y,k;
};
data push_data(int x,int y,int k){
	data temp;
	temp.x=x;
	temp.y=y;
	temp.k=k;
	return temp;
}
void BFS(int x,int y){
	queue <data>q;
	q.push(push_data(x,y,0));
	a[x][y]=0;
	while(!q.empty()){
		data top=q.front();
		q.pop();
		int x=top.x,y=top.y,k=top.k;
		if(x==z&&y==t){
			cout<<k<<endl;
			return;
		}
		if(a[x-1][y]){
			a[x-1][y]=0;
			q.push(push_data(x-1,y,k+1));
		}
		if(a[x+1][y]){
			a[x+1][y]=0;
			q.push(push_data(x+1,y,k+1));
		}
		if(a[x][y-1]){
			a[x][y-1]=0;
			q.push(push_data(x,y-1,k+1));
		}
		if(a[x][y+1]){
			a[x][y+1]=0;
			q.push(push_data(x,y+1,k+1));
		}
	}
	cout<<-1<<endl;
}
int main() {
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int c;
	cin>>c;
	while(c--){
		cin>>n>>m>>x>>y>>z>>t;
		x++;y++;z++;t++;
		for(int i=0;i<=n+1;i++){
			for(int j=0;j<=m+1;j++){
				a[i][j]=0;
			}
		}
		for(int i=1;i<=n;i++){
			for(int j=1;j<=m;j++){
				cin>>a[i][j];
			}
		}
		if(a[x][y]==0){
			cout<<-1<<endl;
			continue;
		}
		BFS(x,y);
	}
}
