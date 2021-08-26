#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
vector<int> a(1000005,0);
vector<long long> b;
void era(){
	for(long long i=2;i<=1000001;i++){
		if(a[i]==0){
			for(long long j=i*i;j<=1000001;j+=i) a[j]=1;
			b.push_back(i);
		}
	}
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	era();
	int t;
	cin>>t;
	while(t--){
		long long n,i=0;
		cin>>n;
		while(b[i]*b[i]<=n){
			i++;
		}
		cout<<i<<endl;
	}
}
