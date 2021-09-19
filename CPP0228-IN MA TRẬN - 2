#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		int m=8*n*n;
	    int a1[m],a2[m],b,c=1,k=1,s=2;
	    a1[0]=b=m+2*n;
	    while(k<m){
	        for(int i=0;i<s;i++){
	            b=a1[k++]=(b-4*n*c);
	            if(k>=m) break;
	        }
	        if(k>=m) break;
	        for(int i=0;i<s;i++){
	            b=a1[k++]=b+c;
	            if(k>=m) break;
	        }
	        c*=-1;
	        s+=2;
	    }
	    for(int i=0;i<m;i++) a2[i]=2*m-a1[i]+1;
	    for(int i=0;i<m;i++) cout<<a1[i]<<" ";
	    cout<<endl;
	    for(int i=0;i<m;i++) cout<<a2[i]<<" ";
	    cout<<endl;
	}
}
