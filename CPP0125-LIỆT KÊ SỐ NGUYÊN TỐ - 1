#include <bits/stdc++.h>
using namespace std;
vector <int> a(1e6+5,0);
void era(){
	a[0]=1;a[1]=1;
	for(long long i=2;i*i<=1000000;i++){
		if(a[i]==0){
			for(long long j=i*i;j<=1000000;j+=i){
				a[j]=1;
			}
		}
	}
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	era();
	int m,n;
	cin>>m>>n;
	if(m>n) swap(m,n);
	for(int i=m;i<=n;i++){
		if(a[i]==0) cout<<i<<" ";
	}
}
