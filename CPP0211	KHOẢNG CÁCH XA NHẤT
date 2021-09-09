#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,s=0;
		cin>>n;
		vector <int> a(n),b(n+1,-1e6);
		for(int i=0;i<n;i++) cin>>a[i];
	    for(int i=a.size()-1;i>=0;i--){
	        b[i]=max(b[i+1],a[i]);
	    }
	    for(int i=0;i<n;i++){
	        int l=i+1,r=n-1,ss=i;
	        while(l<=r){
	            int mid=(l+r)/2;
	            if(a[i]<=b[mid]){
	                ss=max(ss,mid);
	                l=mid+1;
	            }
	            else r=mid-1;
	    	}
	        s=max(s,ss-i);
	    }
	    cout<<s<<endl;
	}
}
