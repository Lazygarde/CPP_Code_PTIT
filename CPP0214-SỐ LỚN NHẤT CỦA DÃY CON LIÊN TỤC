#include<bits/stdc++.h>
using namespace std;
int main(){
    int t;
    cin>>t;
    while(t--){
    	int n,k;
    	cin>>n>>k;
    	int a[n];
    	deque <int> b;
    	for(int i=0;i<n;i++) cin>>a[i];
    	for(int i=0;i<n;i++){
    		while(!b.empty()&&a[b.back()]<=a[i]) b.pop_back();
    		b.push_back(i);
    		while(b.front()+k<=i) b.pop_front();
    		if(i>=k-1) cout<<a[b.front()]<<" ";
		}
		cout<<endl;
	}
}
