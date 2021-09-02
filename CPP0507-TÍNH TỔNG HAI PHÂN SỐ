#include <bits/stdc++.h>
using namespace std;
struct PhanSo{
	long long tu,mau;
};
long long ucln(long long a,long long b){
    while(b!=0){
        long long x=a%b;
        a=b;
        b=x;
    }
    return a;
}
long long bcnn(long long a,long long b){
	return a*b/ucln(a,b);
}
void nhap(struct PhanSo &p){
	cin>>p.tu>>p.mau;
}
void rutgon(struct PhanSo &p){
	long long k=ucln(p.tu,p.mau);
	p.tu/=k;
	p.mau/=k;
}
struct PhanSo tong(struct PhanSo p,struct PhanSo q){
	struct PhanSo x;
	rutgon(p);
	rutgon(q);
	long long k=bcnn(p.mau,q.mau);
	x.mau=k;
	long long d1=k/p.mau*p.tu;
	long long d2=k/q.mau*q.tu;
	x.tu=d1+d2;
	rutgon(x);
	return x;
}
void in(struct PhanSo p){
	cout<<p.tu<<"/"<<p.mau;
}
int main() {
	struct PhanSo p,q;
	nhap(p); nhap(q);
	PhanSo t = tong(p,q);
	in(t);
	return 0;
}
