#include <bits/stdc++.h>
using namespace std;
int main(){
    int n,k,Max=-1,ok=0;
    cin>>n;
    vector <int> a(300, 0);
    for(int i=0;i<n;i++){
        cin>>k;
        a[k]++;
        if(k>Max) Max=k;
    }
    for(int i=1;i<Max;i++){
        if(a[i]==0){
            cout<<i<<endl;
            ok=1;
        }
    }
    if(ok==0) cout<<"Excellent!";
}
