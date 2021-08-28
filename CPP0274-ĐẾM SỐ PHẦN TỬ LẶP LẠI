#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		int a[n],s=0;
		map <int,int> b;
		for(int i=0;i<n;i++){
			cin>>a[i];
			b[a[i]]++;
			if(b[a[i]]==2) s+=2;
			else if(b[a[i]]>2) s++;
		}
		cout<<s<<endl;
	}
}
