#include <bits/stdc++.h>
using namespace std;
vector <int> a(100005,1),b(100005,0);
void era(){
	for(long long i=2;i*i<=100000;i++){
		if(a[i]==1){
			for(long long j=i*i;j<=100000;j+=i) a[j]=0;
		}
	}
	for(int i=2;i<=100000;i++){
		b[i]=b[i-1]+a[i];
	}
}
int main(){
	era();
	int t;
	cin>>t;
	while(t--){
		int l,r;
		cin>>l>>r;
		cout<<b[r]-b[l-1]<<endl;
	}
}
