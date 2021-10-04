#include <bits/stdc++.h>
using namespace std;
vector <int> a(2e6+1);
void era(){
    for(int i=2;i*i<=2e6+1;i++){
        if(a[i]==0){
            for(int j=i*i;j<=2e6+1;j+=i){
                if(a[j]==0) a[j]=i;
            }
        }
    }
    for(int i=2;i<=2e6;i++){
        if(a[i]==0) a[i]=i;
    }
}
int main(){
    era();
    int n,x;
    cin>>n;
    long long s=0;
    while(n--){
    	cin>>x;
        while(x!=1){
            s+=a[x];
            x/=a[x];
        }
    }
    cout<<s;
}
