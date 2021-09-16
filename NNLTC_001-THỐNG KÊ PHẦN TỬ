#include<bits/stdc++.h>
using namespace std;
struct data{
	int n,s;
};
int main(){
	int x;
	vector <data> a;
	while(cin>>x){
		int ok=1;
		for(int j=0;j<a.size();j++){
			if(a[j].n==x){
				ok=0;
				a[j].s++;
				break;
			}
		}
		if(ok==1){
			struct data b;
			b.n=x;
			b.s=1;
			a.push_back(b);
		}
	}
	for(int i=0;i<a.size();i++){
		cout<<a[i].n<<" "<<a[i].s<<endl;
	}
}
