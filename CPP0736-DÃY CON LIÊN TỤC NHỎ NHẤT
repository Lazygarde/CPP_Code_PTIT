#include <iostream>
using namespace std;
int Do(int a[],int n,int x){
    int s= 0,mim=n+1,l=0,r=0;
    while(r<n){
        while(s<=x&&r<n) s+=a[r++];
        while(s>x&&l<n){
            if(r-l<mim) mim=r-l;
            s-=a[l++];
        }
    }
    return mim;
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,x;
		cin>>n>>x;
		int a[n];
		for(int i=0;i<n;i++) cin>>a[i];
		if(Do(a,n,x)==n+1) cout<<-1<<endl;
		else cout<<Do(a,n,x)<<endl;
	}
}
