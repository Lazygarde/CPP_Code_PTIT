#include <bits/stdc++.h>
using namespace std;
int ii=1;
class NhanVien{
	public:
	string manv,ten,gt,ns,dc,ms,nk;
	friend istream &operator>>(istream &input,NhanVien &a){
		if(ii<10) a.manv="0000";
		else a.manv="000";
		a.manv=a.manv+to_string(ii);
		ii++;
		cin.ignore();
		getline(cin,a.ten);
		cin>>a.gt>>a.ns;
		cin.ignore();
		getline(cin,a.dc);
		cin>>a.ms>>a.nk;
		return input;
	}
	friend ostream &operator<<(ostream &output,NhanVien a){
		cout<<a.manv<<" "<<a.ten<<" "<<a.gt<<" "<<a.ns<<" "<<a.dc<<" "<<a.ms<<" "<<a.nk<<endl;
		return output;
	}
};
bool cmp(NhanVien a,NhanVien b){
	string n1=a.ns.substr(6,4);
	string n2=b.ns.substr(6,4);
	string t1=a.ns.substr(3,2);
	string t2=b.ns.substr(3,2);
	string nn1=a.ns.substr(0,2);
	string nn2=b.ns.substr(0,2);
	if(n1==n2){
		if(nn1==nn2) return t1<t2;
		return nn1<nn2;
	}
	return n1<n2;
}
void sapxep(NhanVien a[],int n){
	sort(a,a+n,cmp);
}
int main(){
    NhanVien ds[50];
    int N,i;
    cin >> N;
    for(i=0;i<N;i++) cin >> ds[i];
    sapxep(ds, N);
    for(i=0;i<N;i++) cout << ds[i];
    return 0;
}
