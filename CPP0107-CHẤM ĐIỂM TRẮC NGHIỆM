#include <bits/stdc++.h>
#define endl "\n"
using namespace std;
int main(){
	ios_base::sync_with_stdio(0);
	cin.tie(0);
	int t;
	cin>>t;
	while(t--){
		int n,s=0;
		cin>>n;
		vector <char> a(15),b(15,'A'),c(15,'A');
		b[1]=b[2]=b[8]=b[13]='B';
		b[5]=b[6]=b[10]=b[11]='C';
		b[4]=b[9]=b[14]='D';
		c[4]=c[8]=c[9]=c[13]=c[14]='B';
		c[1]=c[2]=c[5]=c[10]='C';
		c[6]=c[7]=c[11]=c[12]='D';
		for(int i=0;i<15;i++) cin>>a[i];
		if(n==101){
			for(int i=0;i<15;i++){
				if(a[i]==b[i]) s++;
			}
			printf("%.2f\n",(float)10*s/15);
		}
		else{
			for(int i=0;i<15;i++){
				if(a[i]==c[i]) s++;
			}
			printf("%.2f\n",(float)10*s/15);
		}
	}
}
