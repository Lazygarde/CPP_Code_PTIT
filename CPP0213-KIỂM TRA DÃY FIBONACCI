#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int fibo(int n){
	if(n<4) return 1;
	int a=1,b=1;
	while(a<n){
		int k=a+b;
		b=a;
		a=k;
	}
	if(a==n) return 1;
	else return 0;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,x;
		cin>>n;
		for(int i=0;i<n;i++){
			cin>>x;
			if(fibo(x)) cout<<x<<" ";
		}
		cout<<endl;
	}
}
