#include <bits/stdc++.h>
using namespace std;
struct data{
	int m,pos;
};
bool cmp(data a,data b){
	if(a.m==b.m) return a.pos>b.pos;
	return a.m<b.m;
}
int main(){
	int n,k,x;
	cin>>n>>k;
	struct data a[k+1];
	for(int i=0;i<=k;i++){
		a[i].pos=i;
		a[i].m=0;
	}
	for(int i=0;i<n;i++){
		cin>>x;
		a[x].m++;
	}
	sort(a+1,a+k+1,cmp);
	int ii=k;
	while(a[ii].m==a[k].m&&ii>0) ii--;
	if(ii==0||a[ii].m==0) cout<<"NONE";
	else cout<<a[ii].pos; 
}
