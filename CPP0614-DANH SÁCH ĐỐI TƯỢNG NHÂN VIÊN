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
int main(){
    NhanVien ds[50];
    int N,i;
    cin >> N;
    for(i=0;i<N;i++) cin >> ds[i];
    for(i=0;i<N;i++) cout << ds[i];
    return 0;
}
