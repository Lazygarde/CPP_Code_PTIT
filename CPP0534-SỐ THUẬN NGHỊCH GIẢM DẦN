#include <bits/stdc++.h>
using namespace std;
struct data{
	string x;
	int s;
};
bool check(string a){
	int n=a.size();
	for(int i=0;i<=(n-1)/2;i++){
		if(a[i]!=a[n-i-1]) return 0;
	}
	return 1;
}
bool cmp(struct data a,struct data b){
	if(a.x.size()==b.x.size()) return a.x>b.x;
	return a.x.size()>b.x.size();
}
int main(){
	string a;
	vector <data> b;
	while(cin>>a){
		if(a.size()==1) continue;
		if(check(a)){
			int k=-1;
			for(int i=0;i<b.size();i++){
				if(a==b[i].x){
					k=i;
					break;
				}
			}
			if(k==-1){
				struct data c;
				c.x=a;
				c.s=1;
				b.push_back(c);
			}
			else b[k].s++;
		}
	}
	sort(b.begin(),b.end(),cmp);
	for(int i=0;i<b.size();i++) cout<<b[i].x<<" "<<b[i].s<<endl;
}
