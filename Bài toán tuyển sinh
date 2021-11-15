#include <bits/stdc++.h>
using namespace std;
int main(){
    double toan,ly,hoa,s=0;
    string ma,ten,a;
    getline(cin,ma);
    getline(cin,ten);
    cin>>toan>>ly>>hoa;
    s=toan*2+ly+hoa;
    cout<<ma<<" "<<ten<<" ";
    a.push_back(ma[0]);
    a.push_back(ma[1]);
    a.push_back(ma[2]);
    if(a=="KV1"){
        cout<<0.5<<" ";
        a="0.5";
    }
    else if(a=="KV2"){
        cout<<1<<" ";
        a="1";
    }
    else if(a=="KV3"){
        cout<<2.5<<" ";
        a="2.5";
    }
    if(s==(int)s) cout<<(int)s<<" ";
    else cout<<fixed<<setprecision(1)<<s<<" ";
    if(s+stod(a)>=24.0) cout<<"TRUNG TUYEN";
    else cout<<"TRUOT";
}
