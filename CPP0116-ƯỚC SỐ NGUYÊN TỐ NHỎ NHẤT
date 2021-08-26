#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
vector <int> a(10005,0);
void era(){
	for(int i=2;i*i<=10000;i++){
		if(a[i]==0){
			for(int j=i*i;j<=10000;j+=i){
				if(a[j]==0) a[j]=i;
			}
		}
	}
	for(int i=1;i<=10000;i++) if(a[i]==0) a[i]=i;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	era();
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		for(int i=1;i<=n;i++) cout<<a[i]<<" ";
		cout<<endl;
	}
}
