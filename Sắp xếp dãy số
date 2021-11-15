#include <bits/stdc++.h>
using namespace std;
int main(){
    int t;
    cin>>t;
    while(t--){
    	long long n,m,Max=-1e9-2,x,ok=0;
	    vector <long long> a,b;
	    cin>>n>>m;
	    for(int i=0;i<n;i++){
	        cin>>x;
	        if(x>Max) Max=x;
	        if(x>=0) b.push_back(x);
	        else a.push_back(x);
	    }
	    for(int i=0;i<a.size();i++){
	        if(ok==0&&a[i]==Max){
	            cout<<m<<" "<<a[i]<<" ";
	            ok=1;
	        }
	        else cout<<a[i]<<" ";
	    }
	    for(int i=0;i<b.size();i++){
	        if(ok==0&&b[i]==Max){
	            cout<<m<<" "<<b[i]<<" ";
	            ok=1;
	        }
	        else cout<<b[i]<<" ";
		}
	    cout<<endl;
	}
}
