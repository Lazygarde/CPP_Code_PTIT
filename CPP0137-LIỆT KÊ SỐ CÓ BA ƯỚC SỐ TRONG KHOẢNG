#include <bits/stdc++.h>
using namespace std;
vector<int> a(1000005,1);
vector<int> b;
vector<int> pos(1000005);
void era(){
	for(long long i=2;i<=1000001;i++){
		if(a[i]==1){
			b.push_back(i);
			for(long long j=i*i;j<=1000001;j+=i){
				a[j]=0;
			}
		}
		pos[i]=b.size()-1;
	}
}
int main(){
	int t;
	cin>>t;
	era();
	while(t--){
		long long l,r,s=0;
		cin>>l>>r;
		int k=sqrt(l),h=sqrt(r);
		int m=pos[k],n=pos[h];
		cout<<n-m+1<<endl;
	}
}
