#include<bits/stdc++.h>
using namespace std;
int sum(int a,int b[],int m,int c[]){
    if(a==0) return 0;
    if(a==1) return c[0];
    int d=upper_bound(b,b+m,a)-b;
    int k=m-d;
    k+=(c[0]+c[1]);
    if(a==2) k-=(c[3]+c[4]);
    if(a==3) k+=c[2];
    return k;
}
int main(){
	int t;
    cin>>t;
    while(t--){
        int n,m;
        cin>>n>>m;
        int a[n],b[m],c[5]={},s=0;
        for(int i=0;i<n;i++) cin>>a[i];
        for(int i=0;i<m;i++) cin>>b[i];
	    for(int i=0;i<m;i++){
	        if(b[i]<5) c[b[i]]++;
	    }
	    sort(b,b+m);
	    for(int i=0;i<n;i++){
	        s+=sum(a[i],b,m,c);
	    }
        cout<<s<<endl;
    }
}
