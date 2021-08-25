#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int cl(int n){
	int c=0,l=0;
	while(n!=0){
		int k=n%10;
		if(k%2==0) c++;
		else l++;
		n/=10;
	}
	if(c==l) return 1;
	return 0;
}
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int n,s=1;
	cin>>n;
	int a=1,b=10;
	for(int i=0;i<n-1;i++){
		a*=10;
		b*=10;
	}
	b--;
	for(int i=a;i<=b;i++){
		if(cl(i)){
			cout<<i<<" ";
			s++;
			if(s%10==1) cout<<endl;
		}
	}
}
