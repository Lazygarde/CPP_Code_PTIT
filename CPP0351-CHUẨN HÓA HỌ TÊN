#include<bits/stdc++.h>
using namespace std;
void dev(string a,vector <string> &b){
	string x="";
	for(int i=0;i<a.size();i++){
		if(a[i]>='A'&&a[i]<='Z') a[i]+=32;
		if(a[i]==' '){
			b.push_back(x);
			x="";
		}
		else x=x+a[i];
	}
	b.push_back(x);
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int x;
		cin>>x;
		cin.ignore();
		string a;
		getline(cin,a);
		vector <string> b;
		dev(a,b);
		int n=b.size();
		for(int i=0;i<n;i++){
			if(b[i]!="") b[i][0]-=32;
		}
		if(x==1){
			n--;
			while(b[n]=="") n--;
			cout<<b[n]<<" ";
			for(int i=0;i<n;i++) if(b[i]!="") cout<<b[i]<<" ";
		}
		else{
			int k=0;
			while(b[k]=="") k++;
			for(int i=k+1;i<n;i++) if(b[i]!="") cout<<b[i]<<" ";
			cout<<b[k];
		}
		cout<<endl;
	}
}
