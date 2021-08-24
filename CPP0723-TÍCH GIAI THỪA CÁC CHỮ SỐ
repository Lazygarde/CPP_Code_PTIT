#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,b[10]={};
		cin>>n;
		string a;
		cin>>a;
		for(int i=0;i<n;i++){
			if(a[i]=='2') b[2]++;
			else if(a[i]=='3') b[3]++;
			else if(a[i]=='4'){
				b[2]+=2;
				b[3]++;
			}
			else if(a[i]=='5') b[5]++;
			else if(a[i]=='6'){
				b[3]++;
				b[5]++;
			}
			else if(a[i]=='7') b[7]++;
			else if(a[i]=='8'){
				b[2]+=3;
				b[7]++;
			}
			else if(a[i]=='9'){
				b[2]++;
				b[3]+=2;
				b[7]++;
			}
		}
		for(int i=7;i>=2;i--){
			for(int j=0;j<b[i];j++) cout<<i;
		}
		cout<<endl;
	}
}
