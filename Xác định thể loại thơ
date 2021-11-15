#include <bits/stdc++.h>
using namespace std;
int main(){
	int n;
	cin>>n;
	cin.ignore();
	vector <int> a,b;
	while(n--){
		string s;
		getline(cin,s);
		int k=0;
		for(int i=1;i<s.size()-1;i++){
			if((s[i]==' '&&s[i]+1==' ')||(s[i]==' '&&s[i-1]==' ')) continue;
			if(s[i]==' ') k++;
		}
		a.push_back(k);
	}
	int i=0;
	while(i<a.size()){
		if(a[i]==5){
			if(a[i+1]!=7){
				i+=2;
				continue;
			}
			i+=2;
			while(a[i]==5&&i<a.size()){
				i+=2;
			}
			b.push_back(1);
		}
		else if(a[i]==6){
			b.push_back(2);
			i+=4;
		}
		else i++;
	}
	cout<<b.size()<<endl;
	for(int i=0;i<b.size();i++) cout<<b[i]<<endl;
}
