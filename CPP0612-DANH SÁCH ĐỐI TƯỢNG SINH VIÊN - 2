#include <bits/stdc++.h>
using namespace std;
int ii=1;
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
void chuanhoa(string &a){
	vector <string> b;
	dev(a,b);
	a="";
	for(int i=0;i<b.size();i++){
		if(b[i]!=""){
			b[i][0]-=32;
			a=a+b[i];
			a=a+" ";
		}
	}
}
class SinhVien{
	public:
	string masv,ten,lop,ns;
	float gpa;
	friend istream &operator>>(istream &input,SinhVien &a){
		cin.ignore();
		getline(cin,a.ten);
		cin>>a.lop>>a.ns>>a.gpa;
		return input;
	}
	friend ostream &operator<<(ostream &output,SinhVien a){
		if(ii<10) a.masv="B20DCCN00";
		else a.masv="B20DCCN0";
		a.masv=a.masv+to_string(ii);
		if(a.ns[1]=='/') a.ns="0"+a.ns;
		if(a.ns[4]=='/') a.ns.insert(a.ns.begin()+3,'0');
		ii++;
		chuanhoa(a.ten);
		cout<<a.masv<<" "<<a.ten<<a.lop<<" "<<a.ns;
		printf(" %.2f\n",a.gpa);
		return output;
	}
};
int main(){
    SinhVien ds[50];
    int N, i;
    cin >> N;
    for(i=0;i<N;i++){
        cin >> ds[i];
    }
    for(i=0;i<N;i++){
        cout << ds[i];
    }
    return 0;
}
