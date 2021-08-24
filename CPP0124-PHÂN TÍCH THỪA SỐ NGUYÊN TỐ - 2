#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int n;
	cin>>n;
	for(int i=2;i<=sqrt(n);i++){
		int s=0;
		while(n%i==0){
			s++;
			n/=i;
		}
		if(s>0) cout<<i<<" "<<s<<endl;
	}
	if(n>1) cout<<n<<" "<<1;
}
