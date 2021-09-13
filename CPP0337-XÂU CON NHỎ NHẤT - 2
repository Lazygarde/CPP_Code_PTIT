#include <bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		string a;
		cin>>a;
		int n=a.size(),s=0,b[26]={},c[26]={},mim=1e6,d=0,l=0,r=-1;
	    for(int i=0;i<n;i++){
	        if(b[a[i]-'a']==0){
	            b[a[i]-'a']=1;
	            s++;
	        }
	    }
	    for(int i=0;i<n;i++){
	        c[a[i]-'a']++;
	        if(c[a[i]-'a']==1) d++;
	        if(d==s){
	            while(c[a[l]-'a']>1){
	                if(c[a[l]-'a']>1) c[a[l]-'a']--;
	                l++;
	            }
	            int lw=i-l+1;
	            if(mim>lw){
	                mim=lw;
	                r=l;
	            }
	        }
	    }
	    cout<<mim<<endl;
	}
}
