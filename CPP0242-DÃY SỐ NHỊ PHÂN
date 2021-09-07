#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		int n,maxx=0;
	    cin>>n;
	    int a[n+1],b[n+1];
	    a[0]=b[0]=0;
	    for(int i=1;i<=n;i++){
	    	cin>>a[i];
	    	a[i]+=a[i-1];
		}
	    for(int i=1;i<=n;i++){
	    	cin>>b[i];
	    	b[i]+=b[i-1];
		}
	    for(int i=1;i<=n;i++){
	    	for(int j=i+maxx;j<=n;j++){
	    		if(a[j]-a[i-1]==b[j]-b[i-1]){
	    			if(j-i+1>maxx) maxx=j-i+1;
				}
			}
		}
	    cout<<maxx<<endl;
	}
}
