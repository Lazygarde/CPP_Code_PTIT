#include <bits/stdc++.h>
using namespace std;
struct SinhVien{
	string ten,lop,ns;
	float s;
};
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
void chuanhoa(string a){
	vector <string> b;
	dev(a,b);
	for(int i=0;i<b.size();i++){
		if(b[i]!=""){
			b[i][0]-=32;
			cout<<b[i]<<" ";
		}
	}
}
void nhap(SinhVien a[],int n){
	for(int i=0;i<n;i++){
		cin.ignore();
		getline(cin,a[i].ten);
		cin>>a[i].lop>>a[i].ns>>a[i].s;
	}
}
void in(SinhVien a[],int n){
	for(int i=0;i<n;i++){
		if(a[i].ns[1]=='/') a[i].ns.insert(0,1,'0');
		if(a[i].ns[4]=='/') a[i].ns.insert(3,1,'0');
		if(i<9) cout<<"B20DCCN00";
		else cout<<"B20DCCN0";
		cout<<i+1<<" ";
		chuanhoa(a[i].ten);
		cout<<a[i].lop<<" "<<a[i].ns<<" ";
		printf("%.2f\n",a[i].s);
	}
}
int main(){
	struct SinhVien ds[50];
    int N;
    cin >> N;
    nhap(ds, N);
    in(ds, N);
    return 0;
}
