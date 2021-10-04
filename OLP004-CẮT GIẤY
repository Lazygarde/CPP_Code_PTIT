#include <stdio.h>
int a[6001][6001];
int min(int n,int m){
	if(n<m) return n;
	return m;
}
int main(){
	int n,m,c,d,e,x,y,s=0;
	scanf("%d%d%d%d%d",&n,&m,&c,&d,&e);
	for(int i=0;i<c;i++){
		scanf("%d%d",&x,&y);
		a[x][y]=1;
	}
	for(int i=1;i<=n;i++){
		for(int j=1;j<=m;j++){
			a[i][j]+=a[i-1][j]+a[i][j-1]-a[i-1][j-1];
		}
	}
	int l=d,r=min(n,m);
	while(l<=r){
		int k=(l+r)/2,ok=0;
		for(int i=1;i<=n-k+1;i++){
			for(int j=1;j<=m-k+1;j++){
				int f=a[i+k-1][j+k-1]-a[i-1][j+k-1]-a[i+k-1][j-1]+a[i-1][j-1];
				if(f<=e){
					ok=1;
					break;
				}
			}
			if(ok==1) break;
		}
		if(ok==1){
			s=k;
			l=k+1;
		}
		else r=k-1;
	}
	printf("%d",s-s%d);
}
