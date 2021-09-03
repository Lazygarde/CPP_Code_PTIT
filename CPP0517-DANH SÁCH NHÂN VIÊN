#include <bits/stdc++.h>
using namespace std;
struct NhanVien{
	string ten,gt,ns,dc,ms,nk;
};
void nhap(struct NhanVien &a){
	cin.ignore();
	getline(cin,a.ten);
	cin>>a.gt>>a.ns;
	cin.ignore();
	getline(cin,a.dc);
	cin>>a.ms>>a.nk;
}
void inds(struct NhanVien a[],int n){
	for(int i=0;i<n;i++){
		int k=i+1,s=0;
		while(k!=0){
			s++;
			k/=10;
		}
		if(s==1) cout<<"0000";
		else cout<<"000";
		cout<<i+1<<" "<<a[i].ten<<" "<<a[i].gt<<" "<<a[i].ns<<" "<<a[i].dc<<" "<<a[i].ms<<" "<<a[i].nk<<endl;
	}
}
int main(){
	struct NhanVien ds[50];
    int N,i;
    cin >> N;
    for(i = 0; i < N; i++) nhap(ds[i]);
    inds(ds,N);
    return 0;
}
