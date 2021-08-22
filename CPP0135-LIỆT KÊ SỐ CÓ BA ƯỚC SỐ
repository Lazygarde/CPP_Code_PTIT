#include <bits/stdc++.h>
using namespace std;
vector<int> a(1000005,1);
vector<int> b;
void era(){
	for(long long i=2;i<=1000001;i++){
		if(a[i]==1){
			b.push_back(i);
			for(long long j=i*i;j<=1000001;j+=i){
				a[j]=0;
			}
		}
	}
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	era();
	while(t--){
		int n,i=0;
		cin>>n;
		while(b[i]*b[i]<=n){
			cout<<b[i]*b[i]<<" ";
			i++;
		}
		cout<<endl;
	}
}
