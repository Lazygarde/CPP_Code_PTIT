#include <bits/stdc++.h>
using namespace std;
int ii=0;
struct NhanVien{
    string stt,ten,gt,ns,nm,th,ng,dc,id,nn;
};
bool cmp(NhanVien a,NhanVien b){
    if(a.nm==b.nm){
        if(a.ng==b.ng) return a.th<b.th;
        else return a.ng<b.ng;
    }
    return a.nm<b.nm;
}
void nhap(NhanVien &p){
    cin.ignore();
    getline(cin,p.ten);
    cin>>p.gt>>p.ns;
    cin.ignore();
    getline(cin, p.dc);
    cin>>p.id>>p.nn;
    if(p.ns[1]=='/') p.ns="0"+p.ns;
    if(p.ns[4]=='/') p.ns.insert(p.ns.begin()+3,'0');
    p.ng+=p.ns[0];p.ng+=p.ns[1];
    p.th+=p.ns[3];p.th+=p.ns[4];
    p.nm+=p.ns[6];p.nm+=p.ns[7];
    p.nm+=p.ns[8];p.nm+=p.ns[9];
    if(p.nn[1]=='/') p.nn="0"+p.nn;
    if(p.nn[4]=='/') p.nn.insert(p.nn.begin()+3,'0');
    ii++;
    if(ii>9) p.stt="000"+to_string(ii);
    else p.stt="0000"+to_string(ii);
}
void sapxep(NhanVien p[],int n){
    sort(p,p+n,cmp);
}
void inds(NhanVien p[],int n){
    for(int i=0;i<n;i++){
        cout<<p[i].stt<<" "<<p[i].ten<<" "<<p[i].gt<<" "<<p[i].ns<<" ";
        cout<<p[i].dc<<" "<<p[i].id<<" "<<p[i].nn<<endl;
    }
}
int main(){
    struct NhanVien ds[50];
    int N,i;
    cin >> N;
    for(i = 0; i < N; i++) nhap(ds[i]);
    sapxep(ds, N);
    inds(ds, N);
    return 0;
}
