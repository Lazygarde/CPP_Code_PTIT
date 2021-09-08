#include <bits/stdc++.h>
using namespace std;
struct data{
    int stt;
    string ten,nhom;
    double lai;
};
bool cmp(data a,data b){
    return a.lai>b.lai;
}
int main(){
    int n;
    cin>>n;
    double b,c;
    vector <data> a(n);
    for(int i=0;i<n;i++){
        cin.ignore();
        a[i].stt=i+1;
        getline(cin,a[i].ten);
        getline(cin,a[i].nhom);
        cin>>b>>c;
        a[i].lai=c-b;
    }
    sort(a.begin(),a.end(),cmp);
    for(int i=0;i<n;i++){
        cout<<a[i].stt<<" "<<a[i].ten<<" "<<a[i].nhom;
        printf(" %.2lf\n",a[i].lai);
    }
}
