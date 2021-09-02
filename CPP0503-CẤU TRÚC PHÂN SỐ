#include <bits/stdc++.h>
using namespace std;
struct PhanSo{
	long long tu,mau;
};
long long ucln(long long a, long long b) {
    while(b!=0){
        long long x=a%b;
        a=b;
        b=x;
    }
    return a;
}
void nhap(struct PhanSo &p){
	cin>>p.tu>>p.mau;
}
void rutgon(struct PhanSo &p){
	long long k=ucln(p.tu,p.mau);
	p.tu/=k;
	p.mau/=k;
}
void in(struct PhanSo p){
	cout<<p.tu<<"/"<<p.mau;
}
int main(){
	struct PhanSo p;
	nhap(p);
	rutgon(p);
	in(p);
	return 0;
}
